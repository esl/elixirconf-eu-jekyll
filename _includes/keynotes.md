<div class="section speakers" id="speakers">
    <h1 class="title">KEYNOTES</h1>
    <hr/>
    <!-- <p class="section-text">
    
  </p> -->
    <div class="items-container">
        {% assign sorted = site.keynotes | sort: "relevance"  %}
        {% for keynotes in sorted %}
            <div class="item">
                <a href="{{site.baseurl}}{{ keynotes.url }}" class="item-head-link">
                    <div class="img" style="background-image: url('{{site.baseurl}}/assets/images/speakers/{{ keynotes.pic_url }}');">
                        <i class="fa fa-plus-circle"></i>
                    </div>
                    <h4 class="item-name">
                        {{ keynotes.firstname }}
                        <br/>
                        {{keynotes.lastname}}
                    </h4>
                </a>
                <p class="item-position">{{ keynotes.position }}</p>
                <!-- <p class="item-training">Talk:
                    {{ keynotes.talk }}</p> -->
                {% assign filtered_talks = site.talks | where: 'keynotes',
      keynotes.short_name %}
                {% for talk in filtered_talks %}
                    <a href="{{site.baseurl}}{{ talk.url }}">
                        <p class="item-training">Talk:
                            {{ talk.title }}</p>
                    </a>
                {% endfor %}
                {% assign filtered_trainings = site.trainings | where:
      'keynotes', keynotes.short_name %}
                {% for training in filtered_trainings %}
                    <a href="{{site.baseurl}}{{ training.url }}">
                        <p class="item-training">Training:
                            {{ training.title }}</p>
                    </a>
                {% endfor %}
            </div>
        {% endfor %}
    </div>
</div>
