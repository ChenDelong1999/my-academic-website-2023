---
# Leave the homepage title empty to use the site title
title: Delong Chen
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    id: news
    content:
      title: News
      text: "
      - **2023-04-22**. Our paper [_\"Few-shot Classification via Ensemble Learning with Multi-Order Statistics\"_](publication/ijcai2023few) is accepted by IJCAI-23! Our proposed model achieves SoTA few-shot classification accuracy on  CUB, n miniImageNet, tiredImageNet, and CIFAR-FS dataset. See pre-print [here](https://arxiv.org/abs/2305.00454).
      <br /><br />

      - **2023-03-11**. The MEP-3M dataset, previously awarded as IJCAI 2021 LTDL Best Dataset Paper, is now extended and published at _Pattern Recognition_. See details [here](publication/pr2023mep).
      <br /><br />

      - **2023-03-08**. I joined Xiaobing.AI (previously 微软小冰), and started to work on multi-modal large language models with [Baoyuan Wang](https://sites.google.com/site/zjuwby/) and [Jianfeng Liu](https://www.linkedin.com/in/jianfeng-liu-9539897b/).
      <br /><br />

      - **2023-10-10**. I started my internship under the supervision of [Dr. Bei Liu](https://www.microsoft.com/en-us/research/people/libei) at MSRA. My research project is related to egocentric vision language learning.
      <br /><br />

      - **2022-07-08**. Our [comprehensive survey](publication/aire2022deep/) on Deep Learning Based Single Sample Per Person Face Recognition is now published in _Artificial Intelligence Review_. 
      <br /><br />

      - **2022-06-29**. My graduation thesis _\"Music-driven Conducting Motion Generation based on Motion Decomposition and Self-supervised Cross-modal Perceptual Loss\"_ [《基于动态频域分解与跨模态感知的乐队指挥动作生成系统》](uploads/陈德龙本科毕业论文_基于动态频域分解与自监督跨模态感知的乐队指挥动作生成.pdf), previously awarded as Outstanding Graduation Thesis of HHU (河海大学优秀毕业论文), is now awarded as the [First Class of Outstanding Graduation Thesis of Jiangsu Province (江苏省优秀毕业论文一等奖)](http://jyt.jiangsu.gov.cn/art/2022/6/29/art_58320_10520413.html) !
      <br /><br />

      - **2022-06-23**. Our paper [_\"Prototypical Contrastive Language Image Pretraining\"_](publication/arxiv2022prototypical/) is finished at Megvii Technology. The [pre-print](https://arxiv.org/abs/2206.10996) and [codes](https://github.com/megvii-research/protoclip) are now available. We developed a prototype-based approach for improved vision language pretraining, which achieved an +5.81% ImageNet linear probing improvement and an +2.01% ImageNet zero-shot classification improvement compared to CLIP.
      <br /><br />

      - **2022-03-10**. Our paper [_\"Self-Supervised Music Motion Synchronization Learning for Music-Driven Conducting Motion Generation\"_](publication/jcst2022self/) is accepted by SCI (and CCF-B) indexed journal JCST. The [ConductorMotion100](https://github.com/ChenDelong1999/VirtualConductor) dataset has been made public as a track of [The 1st Prospective Cup Meta-Intelligent Data Challenge](http://prospective.tocenet.org/)（首届国际“远见杯”元智能数据挑战大赛）hold by [Jiangsu Computer Society](https://www.jscs.org.cn/x1.php?id=770)（江苏省计算机学会）.
      <br /><br />

      - **2021-09-22**. I begin to work at [MEGVII Technology](https://megvii.com/) (旷视研究院) as a research intern. My research project is related to multimodal self-supervised learning and CLIP-style vision-language pretraining.
      <br /><br />

      - **2021-08-21**. I received a Best Demo Award from [IEEE ICME\'21](http://2021.ieeeicme.org/2021.ieeeicme.org/best_demo_awards.html), a Best Dataset Paper Award from [IJCAI\'21 LTDL workshop](https://ltdl-ijcai21.github.io/submission.html), and a Best Presentation Award from [IEEE BDAI\'21](http://www.bdai.net/2021.html).
      <br /><br />

      - **2021-07-01**. I received my B.S. degree in computer science from [Hohai University (河海大学)](https://en.hhu.edu.cn/) in Nanjing, China, and begin to work as research assistant at the Artificial Intelligence of Multi-modality Group ([AIM Group](https://multimodality.group/)) under the supervision of [Prof. Fan Liu](https://multimodality.group/author/%E5%88%98%E5%87%A1/).
      <br /><br />

      - **1999-03-19**. I was born in Shunde, Guangdong（广东，顺德）, which has a lot of delicious food."
    design:
      columns: '1'

  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Photography
  #         description: 10%
  #         icon: camera-retro
  #         icon_pack: fas
  - block: collection
    id: featured
    content:
      count: 100
      title: Featured Papers
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '1'
      view: 5
  - block: collection
    id: publications
    content:
      count: 100
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: 4
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Ph.D. Study (Incomming)
          company: Hong Kong University of Science and Technology (HKUST)
          company_url: 'https://hkust.edu.hk/'
          company_logo: ''
          location: Hong Kong
          date_start: '2023-09-01'
          date_end: '2027-09-01'
          description: 

        - title: Research Intern
          company: Xiaobing.AI (XiaoIce/微软小冰)
          company_url: 'https://www.xiaoice.com/'
          company_logo: ''
          location: Beijing
          date_start: '2023-03-01'
          date_end: ''
          description: Multi-modal Large Language Models, Conversational AI
        
        - title: Research Intern
          company: Microsoft Research Asia (MSRA)
          company_url: 'https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/'
          company_logo: ''
          location: Beijing
          date_start: '2022-10-01'
          date_end: '2023-01-01'
          description: Egocentric vision-language learning
        
        - title: Research Intern
          company: Megvii Research (旷视研究院)
          company_url: 'https://en.megvii.com/'
          company_logo: ''
          location: Beijing
          date_start: '2021-09-01'
          date_end: '2022-09-01'
          description: Large-scale vision-language pre-training

        - title: Research Assistant
          company: AIM Group, Hohai University (河海大学多模态人工智能实验室)
          company_url: 'https://multimodality.group'
          company_logo: ''
          location: Nanjing (Remote)
          date_start: '2021-09-01'
          date_end: ''
          description: |2-
              Lead a team of graduate students working on research projects include:
              * Vision-language learning for earth observations (satellite and UAV images)
              * Few-shot learning for visual recognition
              * Hydrological time-series forecasting
              * Music-motion pretraining for beat tracking
        
        - title: Orchestra Leader and Concert Master
          company: Symphony Orchestra of Hohai University (河海大学管弦乐团)
          company_url: ''
          company_logo: 
          location: Nanjing
          date_start: '2019-05-01'
          date_end: '2020-09-01'
          description: 

        - title: Summer Program
          company: The University of British Columbia (UBC)
          company_url: 'https://www.ubc.ca/'
          company_logo: ''
          location: Vancuver, Canada
          date_start: '2018-07-15'
          date_end: '2021-08-15'
          description: |2-
              Two Courses Taken
              * Computation for Natural Language Processing (scored 97/100)
              * Linguistics for Natural Language Processing (scored 85/100)

        - title: Undergraduate Study
          company: Hohai University (河海大学)
          company_url: 'https://en.hhu.edu.cn/'
          company_logo: ''
          location: Nanjing
          date_start: '2017-09-01'
          date_end: '2021-06-01'
          description: |2-
            * Bachelor of Science degree in Computer Science
            * Excellent Graduate Student
            * First-class Outstanding Graduation Thesis of Jiangsu Province
    design:
      columns: '2'
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  - block: markdown
    id: awards
    content:
      title: Selected awards, prizes, and honors
      text: "
- **2022-06.**	江苏省优秀本科毕业论文一等奖 
  <br /> First Class of Outstanding Graduation Thesis of Jiangsu Province.
  <br /><br />

- **2021-08.**	Best Dataset Paper Award at _Long-Tailed Distribution Learning Workshop, IJCAI 2021_
  <br /><br />

- **2021-07.**	Best Demo Award at _IEEE International Conference on Multimedia and Expo (ICME) 2021_
  <br /><br />

- **2021-07.**	Best Presentation Winner at _2021 4th International Conference on Big Data and Artificial Intelligence_
  <br /><br />

- **2021-06.**	河海大学2021届本科优秀毕业设计 
  <br /> Outstanding Graduation Thesis of Hohai University in 2021
  <br /><br />

- **2021-06.** 河海大学2021届本科“优秀毕业生”荣誉称号 
  <br /> 	Excellent Graduate Student of Hohai University (highest honor)
  <br /><br />

- **2021-04.** 2020江苏省大学生网络文化节校园歌曲作品征集一等奖 
  <br /> 	First Prize in 2020 Campus Music Competition of Jiangsu Province
  <br /><br />

- **2020-05.**	“江苏省优秀共青团员”称号 
  <br /> Excellent Communist Youth League Member of Jiangsu Province
  <br /><br />

- **2020-10.**	“2019江苏省大学生年度人物”提名奖 
  <br /> Nomination Award for the Person of the Year in Jiangsu Province in 2019
  <br /><br />

- **2020-04.**	2020年河海大学“海韵风华大学生年度人物”称号 
  <br /> Hohai University's 2019 Undergraduate Person of the Year
  <br /><br />

- **2019-06.**	第八届“中国软件杯”大学生软件设计大赛华东分赛区决赛三等奖，团队负责人 
  <br /> Third Prize of The 8th China Software Cup Competition, East China Division Finals (team Leader)
  <br /><br />

- **2017-10.**	河海大学计算机与信息学院2017年新生杯辩论赛“最佳辩手”称号 
  <br /> Best Debater in the 2017 Freshman Cup Debate Competition of the School of Computer and Information, Hohai University	Aug. 2021
  <br /><br />
"
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      # buttons:
      #   - name: All
      #     tag: '*'
      #   - name: Deep Learning
      #     tag: Deep Learning
      #   - name: Other
      #     tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    id: gallery
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'

  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  # - block: contact
  #   id: contact
  #   content:
  #     title: Contact
  #     subtitle:
  #     text: |-
  #       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
  #     # Contact (add or remove contact options as necessary)
  #     email: test@example.org
  #     phone: 888 888 88 88
  #     appointment_url: 'https://calendly.com'
  #     address:
  #       street: 450 Serra Mall
  #       city: Stanford
  #       region: CA
  #       postcode: '94305'
  #       country: United States
  #       country_code: US
  #     directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #     office_hours:
  #       - 'Monday 10:00 to 13:00'
  #       - 'Wednesday 09:00 to 10:00'
  #     contact_links:
  #       - icon: twitter
  #         icon_pack: fab
  #         name: DM Me
  #         link: 'https://twitter.com/Twitter'
  #       - icon: skype
  #         icon_pack: fab
  #         name: Skype Me
  #         link: 'skype:echo123?call'
  #       - icon: video
  #         icon_pack: fas
  #         name: Zoom Me
  #         link: 'https://zoom.com'
  #     # Automatically link email and phone or display as text?
  #     autolink: true
  #     # Email form provider
  #     form:
  #       provider: netlify
  #       formspree:
  #         id:
  #       netlify:
  #         # Enable CAPTCHA challenge to reduce spam?
  #         captcha: false
  #   design:
  #     columns: '2'
---
