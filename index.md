## Intro
My name is <b>ZHAO KongLu</b>. 

My ID number is <b>3221875</b>.

I am a graduate student in MScCT+ at LingNan University. 

## Educational Background
### Master’s Degree, LingNan University
- **Major:** MScCT+
- **ID:** 3221875
- **Duration:** September 2024 - Present

### Bachelor’s Degree, Zhongyuan University of Technology
- **Major:** Software Engineering
- **Duration:** September 2020 - June 2024
  

## Skills
- **Program Languages:** **Python** (Numpy/OpenCV/Pytorch), **C/C++** (Object-oriented programming/OpenMP), **SQL**, **Java**
- **Tools and Technologies:** Linux Programming, Git


## Contact
- **Email:** zhaokonglu@gmail.com
- **WeChat:** zklu0222


<section>
    <h2>News</h2>
    <ul class="news list-unstyled">
        {% for post in site.posts limit: site.front_page_news %}
            {% include news-item.html item=post %}
        {% endfor %}
    </ul>
    {% assign numposts = site.posts | size %}
    {% if numposts >= 1 %}
        <p>
            <span class="fa fa-fw fa-history"></span>
            <a href="{{ site.base }}/blog.html">Older posts&hellip;</a>
        </p>
    {% endif %}
</section>
