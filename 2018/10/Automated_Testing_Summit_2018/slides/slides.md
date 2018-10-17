<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->

## Gentoo Kernel CI 
## Gentoo kernel automated

<!-- .element: class="no-toc-progress" --> <!-- slide not in toc progress bar -->

created by Alice Ferrazzi | Updated as 2018-08-13 | [online][1] | [src][2]


[1]: https://wiki.gentoo.org/wiki/Project:Kernel/Kernel_CI
[2]: https://github.com/gentoo/Gentoo_kernelCI

----

```sh
# kernel:~ $ whoami
```

<div class="fragment" />


* <!-- .element: class="fragment" -->  Gentoo
  * Gentoo Kernel Project Leader
  * Gentoo Kernel Security
  * Gentoo Board Member
  * Gentoo Google Summer of Code Administrator and mentor for rust Gentoo projects
* <!-- .element: class="fragment" -->  Cybertrust Japan
  * OSS Embedded Software Engineer
* <!-- .element: class="fragment" -->  Researcher
  * ACM SIGOPS member number 1727454

----  ----

## 1. Status

----

## Buildbot Based



----

## Kernel Testing

* Qemu based (Someone is testing Raspberry pi) 
* 
* 

----  ----

# 2. Differences with CI loop

----

## fabric

----

## fab and fabfile.py

----

# 3. Special Features

----

Collection of __fabric tasks__:
* set up an [owncloud server][7]
* set up an own android app repository (own [F-Droid server][8])
* set up a linux desktop:
  eg. [configure vim, tmux, solarized colors][9] *(dotfiles on steroids!)*
* set up ...
* <!-- .element: class="fragment" -->
 __set up everything you need for a *reveal.js* presentation__:
 ```sh
 fab setup.revealjs
 ```

[7]: https://github.com/theno/fabsetup/blob/master/howtos/owncloud.md
[8]: https://github.com/theno/fabsetup/blob/master/howtos/f-droid-repo.md
[9]: https://github.com/theno/fabsetup/blob/master/howtos/no-sudo.md


----  ----

# 4. Conclusion and Outlook

----

## Conclusion

* Presentations with __reveal.js__ are fancy and nice
* Writing slides in __Markdown__ is easy
* __fabric__ is a framework for powerfull setup scripts
* __fabsetup__ is a collection of fabric tasks

----

__`fab setup.revealjs`__ (one of this tasks):
  Creates the boilerplate of your presentation:
  * Clean basedir (reveal.js codebase hidden in a subdir)
  * Slides are written in a __Markdown file__
  * Usefull plugins enabled (eg. __footer, toc, menu__)
  * Versioning with __git__
  * Publishing at __github.io__

__`>>just edit the slides.md<<`__  <!-- .element: class="fragment" -->

----

## Outlook

* Publishing with own webserver
  * Implement restricted access
* Custom design
  * Create themes / corporate design
* Explore [more plugins][21]
* [Customize][23] fabsetup task `setup.revealjs`

----  ----

<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->

### *Thank You for Your attention!*
<!-- .element: class="no-toc-progress" -->

![](img/thanks.jpg)
