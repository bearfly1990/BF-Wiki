
```mermaid
    %%{init: { 'logLevel': 'debug', 'theme': 'default' } }%%
       timeline
        title Hitory of My Life(Public)
          幼年(1990-1998): 喇叭线插接线板里
          小学(1997-2002) : 参加田径队(铅球)
                          : 4年级开始长胖
          初中(2002-2005): 初中
          高中(2005-2008): 高中
          大学(2008-2012): 大学
          2012-2014 : 折腾的两年
          2014-2019 : 回SS
          2019-2020 : 换到SB组
          2020-Now : Test
```

```mermaid
   %%{init: { 'logLevel': 'debug', 'theme': 'default' , 'themeVariables': {
              'cScale0': '#ff0000', 'cScaleLabel0': '#ffffff',
              'cScale1': '#00ff00',
              'cScale2': '#0000ff', 'cScaleLabel2': '#ffffff'
       } } }%%
       timeline
        title History of Social Media Platform
          2002 : LinkedIn
          2004 : Facebook : Google
          2005 : Youtube
          2006 : Twitter
          2007 : Tumblr
          2008 : Instagram
          2010 : Pinterest
```

```mermaid
   %%{init: { 'logLevel': 'debug', 'theme': 'default' , 'themeVariables': {
              'cScale0': '#ff0000', 'cScaleLabel0': '#ffffff',
              'cScale1': '#00ff00',
              'cScale2': '#0000ff', 'cScaleLabel2': '#ffffff'
       } } }%%
       timeline
        title History of Social Media Platform
          2002 : LinkedIn
          2004 : Facebook : Google
          2005 : Youtube
          2006 : Twitter
          2007 : Tumblr
          2008 : Instagram
          2010 : Pinterest
```

```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title       Adding GANTT diagram functionality to mermaid
    excludes    weekends
    %% (`excludes` accepts specific dates in YYYY-MM-DD format, days of the week ("sunday") or "weekends", but not the word "weekdays".)

    section A section
    Completed task            :done,    des1, 2014-01-06,2014-01-08
    Active task               :active,  des2, 2014-01-09, 3d
    Future task               :         des3, after des2, 5d
    Future task2              :         des4, after des3, 5d

    section Critical tasks
    Completed task in the critical line :crit, done, 2014-01-06,24h
    Implement parser and jison          :crit, done, after des1, 2d
    Create tests for parser             :crit, active, 3d
    Future task in critical line        :crit, 5d
    Create tests for renderer           :2d
    Add to mermaid                      :until isadded
    Functionality added                 :milestone, isadded, 2014-01-25, 0d

    section Documentation
    Describe gantt syntax               :active, a1, after des1, 3d
    Add gantt diagram to demo page      :after a1  , 20h
    Add another diagram to demo page    :doc1, after a1  , 48h

    section Last section
    Describe gantt syntax               :after doc1, 3d
    Add gantt diagram to demo page      :20h
    Add another diagram to demo page    :48h

```

```mermaid
%%{init: {'theme':'default'}}%%
timeline
 title mermiad时间线图示例(成长)
    section 少年
        2015: 高中
        2018: 大学 
    section 青年
        2023: 工作
        2024: 创业
```

``` mermaid
graph LR
  A[Start] --> B{Error?};
  B -->|Yes| C[Hmm...];
  C --> D[Debug];
  D --> B;
  B ---->|No| E[Yay!];
```

``` mermaid
sequenceDiagram
  autonumber
  Alice->>John: Hello John, how are you?
  loop Healthcheck
      John->>John: Fight against hypochondria
  end
  Note right of John: Rational thoughts!
  John-->>Alice: Great!
  John->>Bob: How about you?
  Bob-->>John: Jolly good!
```

::timeline::

- content: First implementation.
  icon: ':material-rocket-launch-outline:'
  sub_title: 2022-Q1
  title: Launch
- content: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
  icon: ':fontawesome-solid-gem:'
  sub_title: 2022-Q2
  title: New features
- content: Lorem ipsum dolor sit amet.
  icon: ':material-gauge-empty:'
  sub_title: 2022-Q3
  title: More features!
- content: Lorem ipsum dolor sit amet.
  icon: ':material-bug:'
  sub_title: 2022-Q4
  title: Bugs!

::/timeline::

::cards::

- title: Zeus
  content: Lorem ipsum dolor sit amet.
  image: ./img/icons/001-zeus.png

- title: Athena
  content: Lorem ipsum dolor sit amet.
  image: ./img/icons/003-athena.png

- title: Poseidon
  content: Lorem ipsum dolor sit amet.
  image: ./img/icons/007-poseidon.png

- title: Artemis
  content: Lorem ipsum dolor sit amet.
  image: ./img/icons/021-artemis.png

- title: Ares
  content: Lorem ipsum dolor sit amet.
  image: ./img/icons/006-ares.png

- title: Nike
  content: Lorem ipsum dolor sit amet.
  image: ./img/icons/027-nike.png

::/cards::

::gantt::

- title: Definition Phase
  activities:
  - title: Creative Brief
    start: 2022-03-03
    lasts: 1 day
  - title: Graphic Design Research
    start: 2022-03-02
    end: 2022-03-10
    lasts: 2 weeks
  - title: Brainstorming / Mood Boarding
    start: 2022-03-11
    end: 2022-03-20

- title: Creation Phase
  activities:
  - title: Sketching
    start: 2022-03-21
    end: 2022-04-01
  - title: Design Building
    start: 2022-04-02
    end: 2022-04-20
  - title: Refining
    start: 2022-04-21
    end: 2022-04-30

- title: Feedback Phase
  activities:
  - title: Presenting
    start: 2022-04-22
    end: 2022-05-01
  - title: Revisions
    start: 2022-05-02
    end: 2022-05-10

- title: Delivery Phase
  activities:
  - title: Final delivery
    start: 2022-05-11
    end: 2022-05-12

::/gantt::
