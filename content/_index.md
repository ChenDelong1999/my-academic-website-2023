---
# Leave the homepage title empty to use the site title
title: Delong Chen
date: 2023-10-17
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    id: awards
    content:
      title: 'Honors & Awards'
      subtitle: ''
      text: '

- 2023-06.  **Best Paper**<br>at AAAI 2023 Inaugural Summer Symposium Series - AI x Metaverse

- 2022-06.  **江苏省优秀本科毕业论文一等奖**<br>First Class Outstanding Graduation Thesis of Jiangsu Province

- 2021-08. 	**Best Dataset Paper**<br>at Long-Tailed Distribution Learning Workshop, IJCAI 2021

- 2021-07. 	**Best Demo** <br>at IEEE International Conference on Multimedia and Expo (ICME) 2021

- 2021-07. 	**Best Presentation Winner**<br>at 2021 4th International Conference on Big Data and Artificial Intelligence

- 2021-06. 	**河海大学2021届本科优秀毕业设计**<br>Outstanding Graduation Thesis of Hohai University in 2021

- 2021-06.  **河海大学2021届本科“优秀毕业生”荣誉称号**<br>Excellent Graduate Student of Hohai University (highest honor)

- 2021-04.  **2020江苏省大学生网络文化节校园歌曲作品征集一等奖**<br>First Prize in 2020 Campus Music Competition of Jiangsu Province

- 2020-05. 	**“江苏省优秀共青团员”称号**<br>Excellent Communist Youth League Member of Jiangsu Province

- 2020-10. 	**“2019江苏省大学生年度人物”提名奖**<br>Nomination Award for the Person of the Year in Jiangsu Province in 2019

- 2020-04. 	**2020年河海大学“海韵风华大学生年度人物”称号**<br>Hohai University 2019 Undergraduate Person of the Year

- 2019-06. 	**第八届“中国软件杯”大学生软件设计大赛华东分赛区决赛三等奖** （团队负责人）<br>Third Prize of The 8th China Software Cup, East China Division Finals

- 2017-10. 	**河海大学计算机与信息学院2017年新生杯辩论赛“最佳辩手”称号**<br>Best Debater in the 2017 Freshman Cup Debate Competition at Hohai University

'
    design:
      # Choose a layout view
      view: 4
      columns: '2'
  - block: collection
    id: publications
    content:
      count: 100
      title: Selected Publications
      subtitle: ''
      text: |-
        {{% callout %}}
        See full publication list in [**this page**](./publication/) or in [**Google Scholar**](https://scholar.google.com/citations?hl=zh-CN&user=7PW095gAAAAJ&view_op=list_works&sortby=pubdate).
        {{% /callout %}}
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '1'
      view: 5
  - block: experience
    id: experience
    content:
      title: Experience
      subtitle: ''
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Ph.D. Student
          company: "**Hong Kong University of Science and Technology (HKUST)**"
          company_url: 'https://hkust.edu.hk/'
          company_logo: 'hkust'
          location: Hong Kong
          date_start: '2023-09-01'
          date_end: ''
          description: '
          - In [Center for Artificial Intelligence Research (CAiRE)](https://caire.hkust.edu.hk/). Supervisor: [Prof. Pascale Fung](https://pascale.home.ece.ust.hk/about.html) (冯雁)

          ---

          '

        - title: Research Intern
          company: "**Xiaobing.AI (XiaoIce/小冰)**"
          company_url: 'https://www.xiaoice.com/'
          company_logo: ''
          location: 'Beijing'
          date_start: '2023-03-01'
          date_end: '2023-09-01'
          description: '
          Research Projects:
          
          - [Visual Instruction Tuning with Polite Flamingo](https://arxiv.org/abs/2307.01003). arXiv Preprint.
          
          - [Instruct Flamingo: Codebase and Fondation Models for Visual Instruction Tuning](https://github.com/ChenDelong1999/instruct-flamingo). Open Source Project.

          - [Taming Diffusion Models for Music-driven Conducting Motion Generation](https://arxiv.org/abs/2306.10065). AAAI 2023 Inaugural Summer Symposium Series - AI x Metaverse (Best Paper).

          ---

          Mentors: [Baoyuan Wang](https://sites.google.com/site/zjuwby/) (王宝元), [Jianfeng Liu](https://www.linkedin.com/in/jianfeng-liu-9539897b/) (刘剑锋) 
          '
        
        - title: Research Intern
          company: "**Megvii Research (旷视研究院)**"
          company_url: 'https://en.megvii.com/'
          company_logo: 'megvii'
          location: Beijing
          date_start: '2021-09-01'
          date_end: '2022-09-01'
          description: '
          Research Project:

          - [ProtoCILP: Prototypical Contrastive Language Image Pretraining](https://arxiv.org/abs/2206.10996). IEEE TNNLS.


          ---

          Mentors: [Yiping Bao](https://scholar.google.com/citations?hl=zh-CN&user=EB9_W4kAAAAJ) (鲍一平), [Zhao Wu](https://scholar.google.com/citations?hl=zh-CN&user=rhIsGusAAAAJ) (吴曌) 
          '

        - title: Research Assistant
          company: "**AIM Group, Hohai University (河海大学多模态人工智能实验室)**"
          company_url: 'https://multimodality.group'
          company_logo: 'hhu'
          location: Nanjing (Remote)
          date_start: '2021-09-01'
          date_end: '2023-09-01'
          description: '
          
          
          Vision-language Learning:
            
            - [RemoteCLIP: A Vision Language Foundation Model for Remote Sensing](https://arxiv.org/pdf/2306.11029). arXiv Preprint.
            
            - [MEP-3M: A Large-scale Multi-modal E-Commerce Products Dataset](https://www.sciencedirect.com/science/article/pii/S0031320323002194). Pattern Recognition.


          <br/>          
          Few-shot Learning:

            - [Few-shot classification guided by generalization error bound](https://www.sciencedirect.com/science/article/pii/S0031320323006027). Pattern Recognition.

            - [Few-shot Classification via Ensemble Learning with Multi-Order Statistics](https://arxiv.org/pdf/2305.00454). IJCAI-23 (oral).



          <br/>          
          AI for Hydro-Science:

            - [A Simple Baseline for Adversarial Domain Adaptation-based Unsupervised Flood Forecasting](https://arxiv.org/pdf/2206.08105). arXiv Preprint.

            - [Asymmetric exponential loss function for crack segmentation](https://link.springer.com/article/10.1007/s00530-022-00944-4). Multimedia Systems.

            - [Significant Wave Height Prediction based on Wavelet Graph Neural Network](https://ieeexplore.ieee.org/iel7/9515196/9515201/09515293.pdf). IEEE BDAI 2021.
          

          <br/>          
          Face Recogniztion and Analysis:
          
            - [Deep Learning based Single Sample Face Recognition: a Survey](https://link.springer.com/article/10.1007/s10462-022-10240-2). Artificial Intelligence Review.

            - [A Review of Driver Fatigue Detection and Its Advances on the Use of RGB-D Camera and Deep Learning](https://www.sciencedirect.com/science/article/pii/S0952197622003967). Engineering Applications of Artificial Intelligence.
          

          ---

          Supervisor: [Prof. Fan Liu](https://multimodality.group/author/%E5%88%98%E5%87%A1/)(刘凡) 
        '
        - title: Orchestra Leader and Concert Master
          company: "**Symphony Orchestra of Hohai University (河海大学管弦乐团)**"
          company_url: ''
          company_logo: hhu
          location: Nanjing
          date_start: '2019-05-01'
          date_end: '2020-09-01'
          description: 

        - title: Summer Program
          company: "**The University of British Columbia (UBC)**"
          company_url: 'https://www.ubc.ca/'
          company_logo: 'ubc'
          location: Vancuver, Canada
          date_start: '2018-07-15'
          date_end: '2021-08-15'
          description: |2-
              Courses：
              * Computation for Natural Language Processing (scored 97/100)
              * Linguistics for Natural Language Processing (scored 85/100)

        - title: Undergraduate Study (Computer Science)
          company: "**Hohai University (河海大学)**"
          company_url: 'https://en.hhu.edu.cn/'
          company_logo: 'hhu'
          location: Nanjing
          date_start: '2017-09-01'
          date_end: '2021-06-01'
          description: '          

            Thesis Project: 

            - [《基于动态频域分解与跨模态感知的乐队指挥动作生成系统》](uploads/陈德龙本科毕业论文_基于动态频域分解与自监督跨模态感知的乐队指挥动作生成.pdf). 河海大学优秀毕业论文, 江苏省优秀本科毕业论文一等奖. (Outstanding Graduation Thesis of HHU, First-class Outstanding Graduation Thesis of Jiangsu Province)

            - [VirtualConductor: Music-driven Conducting Video Generation System](https://arxiv.org/abs/2108.04350). ICME 2021 (Best Demo Award).

            - [Self-Supervised Music Motion Synchronization Learning for Music-Driven Conducting Motion Generation](https://link.springer.com/content/pdf/10.1007/s11390-022-2030-z.pdf). Journal of Computer Science and Technology.

            '
    design:
      columns: '2'

  - block: portfolio
    id: music
    content:
      title: Music 🎻
      subtitle: ''
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
      view: 0
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    id: gallery
    content:
      title: Gallery 📸
      subtitle: ''
      text: |-
        {{< gallery album="demo" order="desc">}}
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
