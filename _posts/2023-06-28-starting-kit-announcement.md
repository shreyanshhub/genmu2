---
layout: post
title:  "Starting kit now available"
date:   2023-06-28 00:00:00 +0000
categories: announcements
comments: true
---

We are excited to announce the availability of a starting kit for the NeurIPS 2023 Machine Unlearning Challenge! This starting kit provides a foundation for participants to build their unlearning models on the CIFAR-10 dataset.

The starting kit includes: a Jupyter notebook with code to:

* load the CIFAR-10 dataset;
* train a baseline unlearning model; and
* score it using a membership inference attack.

The API used in this baseline unlearning method will be the same one that participants will submit once the competition opens. Hence, we hope that this starting kit will help participants get started in developing and trying out their unlearning methods.


The starting kit can be accessed at [https://github.com/unlearning-challenge/starting-kit](https://github.com/unlearning-challenge/starting-kit).

We hope this starter kit will be helpful to participants as they prepare for the challenge. Please let us know if you have questions through the group [unlearning-challenge](https://groups.google.com/g/unlearning-challenge) or our email [unlearning@chalearn.org](mailto:unlearning@chalearn.org).

Thank you for your interest in the NeurIPS 2023 Machine Unlearning Challenge!

{% if page.comments %}
<div id="disqus_thread"></div>
<script>
    /**
    *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
    *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */
    /*
    var disqus_config = function () {
    this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    */
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://unlearning-challenge.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}
