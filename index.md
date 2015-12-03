---
layout: default
---
{% include about.md %}

# Материалы к занятиям

6.10.2015 Вводное занятие [(презентация — pdf)](pdf/01-Introduction.pdf)

13.10.2015 Фундаментальные модели вычислений [(презентация — pdf)](pdf/02-Models.pdf)

27.10.2015 Формальные системы [(презентация — pdf)](pdf/03-Problem.pdf)

3.11.2015 Model checking [(презентация — pdf)](pdf/04-Model-Checking.pdf)

10.11.2015 λ-исчисление с простыми типами [(презентация - html)](presentations/05-SimplyTypedLambdaCalculus.html)

17.11.2015 Расширения типизированного λ-исчисления [(презентация-html)](presentations/06-SystemF.html)

24.11.2015 Исчисление конструкций [(презентация - html)](presentations/07-CoC.html)

01.12.2015 Индуктивные и коиндуктивные типа [(презентация - html)](presentations/08-Inductive.html)

# Литература
(предварительный список)

Основная литература:

- Б. Пирс. Типы и языки программирования. М.: Лямбда-пресс: Добросвет. 2011.
- A. Chlipala. Certified Programming With Dependent Types. MIT Press. 2013.
- Univalent Foundations Program. Homotopy Type Theory. 2012.
- S. Thompson. Type Theory and Functional Programming. Addison-Wesley, 1991.
- А.Б. Угольников (ред.). Конспект лекций О.Б.Лупанова по курсу "Введение в математическую логику", 2007.
- H. Barendregt. Introduction to generalized type systems. J.Funct.Program, (2):125-154, 1991.

Дополнительная литература (библиографический обзор курса, ссылки на оригинальные публикации, содержащие рассматриваемые в курсе результаты):

- В.А. Васенин, М.А. Кривчиков. Формальные модели программ и языков программирования. Часть 1. Библиографический обзор 1930—1989 гг. Программная инженерия, (5):10–19, 2015.
- В.А. Васенин, М.А. Кривчиков. Формальные модели программ и языков программирования. Часть 2. Современное состояние исследований. Программная инженерия, (6):24–33, 2015.

Перечень ресурсов информационно-телекоммуникационной сети «Интернет»:
- Обновляемая страница курса: http://maxxk.github.io/formal-models-2015/
- М.Р. Пентус. Введение в математическую логику. Конспект лекций на механико-математическом факультете МГУ, весна 2006. http://lpcs.math.msu.su/~pentus/ftp/mehmat/vmlk06le.pdf

Электронные версии книг из списка основной литературы курса:
- A. Chlipala. Certified Programming With Dependent Types. http://adam.chlipala.net/cpdt/
- Univalent Foundations Program. Homotopy Type Theory.  http://homotopytypetheory.org/book/
- S. Thompson. Type Theory and Functional Programming. http://www.cs.kent.ac.uk/people/staff/sjt/TTFP/

Дополнительные ссылки на ресурсы информационно-телекоммуникационной сети Интернет приведены на обновляемой странице курса в материалах лекций.

<!--<div class="home">

  <h1 class="page-heading">Материалы к занятиям:</h1>

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

</div>
-->
