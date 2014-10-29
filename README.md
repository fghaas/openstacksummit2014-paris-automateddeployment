# Automated Deployment of a Highly Available OpenStack Cloud

This repository provides the training materials used for
[the workshop session given on November 3, 2014 at the OpenStack Summit in Paris](https://openstacksummitnovember2014paris.sched.org/event/70cf22bce26516e9d6ae4ae45e966954).

## Resources

You can [view this presentation online](http://goo.gl/mrFFZ7). If you
want to view it locally, after cloning this repository you will have
to check out the
[git submodules](http://git-scm.com/book/en/Git-Tools-Submodules) via
the following commands in order to satisfy the presentation's external
dependencies ([`reveal.js`](https://github.com/hakimel/reveal.js),
[`qrcodejs`](https://github.com/davidshimjs/qrcodejs)) and
[`suse-cloud-vagrant`](https://github.com/SUSE-Cloud/suse-cloud-vagrant).

    git submodule init
    git submodule update

## Authors

*   [Florian Haas](http://openstacksummitmay2014atlanta.sched.org/speaker/fghaas),
    CEO and Principal Consultant at [Hastexo](http://hastexo.com)
*   [Adam Spiers](http://openstacksummitmay2014atlanta.sched.org/speaker/aspiers),
    Senior Software Engineer at [SUSE](http://suse.com/cloud)
