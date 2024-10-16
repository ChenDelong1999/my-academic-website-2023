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

  # - block: collection
  #   id: publications
  #   content:
  #     count: 100
  #     title: Selected Publications
  #     subtitle: ''
  #     text: |-
  #       {{% callout %}}
  #       See full publication list in [**this page**](./publication/) or in [**Google Scholar**](https://scholar.google.com/citations?hl=zh-CN&user=7PW095gAAAAJ&view_op=list_works&sortby=pubdate).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '1'
      # view: 5
  - block: markdown
    id: awards
    content:
      title: ''
      subtitle: ''
      text: '

<div style="display: flex; justify-content: space-between;">
  <!-- 左边的 "Awards & Honors" 列 -->
  <div style="flex: 1; padding-right: 20px;">
    <strong>Awards & Honors</strong>
    <ul>
      <li><strong>Best Paper</strong> at AAAI 2023 Inaugural Summer Symposium Series - AI x Metaverse</li>
      <li><strong>Best Dataset Paper</strong> at Long-Tailed Distribution Learning Workshop, IJCAI 2021</li>
      <li><strong>Best Demo</strong> at IEEE ICME 2021</li>
      <li><strong>Best Presentation</strong> at 2021 IEEE International Conference on Big Data and Artificial Intelligence</li>
      <li> 江苏省优秀本科毕业论文一等奖 </li>
      <li> 河海大学2021届本科“优秀毕业生”荣誉称号</li>
      <li> 2020江苏省大学生网络文化节校园歌曲作品征集一等奖 </li>
      <li> “江苏省优秀共青团员”称号</li>
      <li> “2019江苏省大学生年度人物”提名奖</li>
      <li> 2020年河海大学“海韵风华大学生年度人物”称号</li>
    </ul>
  </div>

  <!-- 右边的 "Professional Services" 列 -->
  <div style="flex: 1; padding-left: 20px;">
    <strong>Reviewer</strong>
    
    <ul>
      <li> ICLR 2024
      <li> NeurIPS 2024
      <li> ACL Rolling Review (ARR): ACL 2024, EMNLP 2024
      <li> ACM Multimedia 2023, 2024
      <li> ACM Transactions on Intelligent Systems and Technology
      <li> Artificial Intelligence Review
    </ul>
    
    <strong>Volunteer</strong>
    <ul>
      <li> AAAI-24
      <li> ACL&apos;24
    </ul>

    <strong>Teaching Assistant</strong>
    <ul>
      <li> ELEC 1200 A System View of Communications (2024 Spring, HKUST)
    </ul>
  </div>
</div>
'
    design:
      # Choose a layout view
      view: 4
      columns: '1'

  - block: markdown
    id: publications
    content:
      title: 'Publications'
      subtitle: ''
      text: '
<i class="fas fa-graduation-cap"></i> See full list of papers in [**Google Scholar**](https://scholar.google.com/citations?user=7PW095gAAAAJ).

<br>

<div style="display: flex; justify-content: space-between; align-items: center;  margin-bottom: 25px;">
  <div style="flex-grow: 1;">
    <span><strong><u>Delong Chen</u></strong>, Samuel Cahyawijaya, Jianfeng Liu, Baoyuan Wang, Pascale Fung</span>
    <br>
    <span><a href="https://arxiv.org/abs/2402.14327"><strong>Subobject-level Image Tokenization</strong></a></span>
    <br><span>arXiv Preprint, 2024. <a href="https://github.com/ChenDelong1999/subobjects"> [<i class="fab fa-github"></i> code]</a></span>
  </div>
  <img src="figures/subobject.png" style="width: auto; height: 120px; object-fit: cover; margin-left: 10px;" />
</div>

<div style="display: flex; justify-content: space-between; align-items: center;  margin-bottom: 25px;">
  <div style="flex-grow: 1;">
    <span><strong><u>Delong Chen</u></strong>, Samuel Cahyawijaya, Etsuko Ishii, Ho Shu Chan, Yejin Bang, Pascale Fung</span>
    <br>
    <span><a href="https://arxiv.org/abs/2405.00485"><strong>What Makes for Good Image Captions?</strong></a></span>
    <br>
    <span>NeurIPS 2024 Workshop on Machine Learning and Compression.</span>
  </div>
  <img src="figures/good_image_captions.png" style="width: auto; height: 120px; object-fit: cover; margin-left: 10px;" />
</div>

<div style="display: flex; justify-content: space-between; align-items: center;  margin-bottom: 25px;">
  <div style="flex-grow: 1;">
    <span>Samuel Cahyawijaya*, <strong><u>Delong Chen</u></strong>*, Yejin Bang*, Leila Khalatbari, Bryan Wilie, Ziwei Ji, Etsuko Ishii, Pascale Fung*</span>
    <br>
    <span><a href="https://arxiv.org/abs/2404.07900"><strong>High-Dimension Human Value Representation in Large Language Models</strong></a></span>
    <br>
    <span>arXiv Preprint, 2024. <a href="https://github.com/HLTCHKUST/UniVaR">[<i class="fab fa-github"></i> code]</a></span>
  </div>
  <img src="figures/human_value_representation.jpg" style="width: auto; height: 120px; object-fit: cover; margin-left: 10px;" />
</div>

<div style="display: flex; justify-content: space-between; align-items: center;  margin-bottom: 25px;">
  <div style="flex-grow: 1;">
    <span>Fan Liu*✉, <strong><u>Delong Chen</u></strong>*✉, Zhangqingyun Guan, Xiaocong Zhou, Jiale Zhu, Jun Zhou</span>
    <br>
    <span><a href="https://arxiv.org/abs/2306.11029"><strong>RemoteCLIP: A Vision Language Foundation Model for Remote Sensing</strong></a></span>
    <br>
    <span>IEEE Transactions on Geoscience and Remote Sensing (TGRS), 2024. <a href="https://github.com/ChenDelong1999/RemoteCLIP">[<i class="fab fa-github"></i> code]</a></span>
  </div>
  <img src="figures/remoteclip.png" style="width: auto; height: 120px; object-fit: cover; margin-left: 10px;" />
</div>

<div style="display: flex; justify-content: space-between; align-items: center;  margin-bottom: 25px;">
  <div style="flex-grow: 1;">
    <span><strong><u>Delong Chen</u></strong>, Jianfeng Liu, Wenliang Dai, Baoyuan Wang</span>
    <br>
    <span><a href="https://arxiv.org/abs/2307.01003"><strong>Visual Instruction Tuning with Polite Flamingo</strong></a></span>
    <br>
    <span>Thirty-Eighth AAAI Conference on Artificial Intelligence (AAAI), 2024. <span style="color:red">(Oral Presentation)</span> <a href="https://github.com/ChenDelong1999/polite-flamingo">[<i class="fab fa-github"></i> code]</a></span>
  </div>
  <img src="figures/polite_flamingo.png" style="width: auto; height: 120px; object-fit: cover; margin-left: 10px;" />
</div>

<div style="display: flex; justify-content: space-between; align-items: center;  margin-bottom: 25px;">
  <div style="flex-grow: 1;">
    <span><strong><u>Delong Chen</u></strong>, Zhao Wu, Fan Liu, Zaiquan Yang, Huaxi Huang, Ying Tan, Erjin Zhou</span>
    <br>
    <span><a href="https://arxiv.org/abs/2206.10996"><strong>ProtoCLIP: Prototypical Contrastive Language Image Pretraining</strong></a></span>
    <br>
    <span>IEEE Transactions on Neural Networks and Learning Systems (TNNLS), 2023. <a href="https://github.com/megvii-research/protoclip">[<i class="fab fa-github"></i> code]</a></span>
  </div>
  <img src="figures/protoclip.png" style="width: auto; height: 120px; object-fit: cover; margin-left: 10px;" />
</div>

<div style="display: flex; justify-content: space-between; align-items: center;  margin-bottom: 25px;">
  <div style="flex-grow: 1;">
    <span>Xinyu Zhou🌹*, <strong><u>Delong Chen</u></strong>*, Samuel Cahyawijaya, Xufeng Duan, Zhenguang G. Cai</span>
    <br>
    <span><a href="https://arxiv.org/abs/2409.12435"><strong>Linguistic Minimal Pairs Elicit Linguistic Similarity in Large Language Models</strong></a></span>
    <br>
    <span>NeurIPS 2024 Workshop on Foundation Model Interventions (MINT). <a href="https://github.com/ChenDelong1999/Linguistic-Similarity">[<i class="fab fa-github"></i> code]</a></span>
  </div>
  <img src="figures/linguistic_similarity.png" style="width: auto; height: 120px; object-fit: cover; margin-left: 10px;" />
</div>


\* Joint First Authors / Equal Contribution
<br>
✉ Corresponding Authors
'
    design:
      # Choose a layout view
      view: 1
      columns: '1'

  - block: portfolio
    id: music
    content:
      title: Music 🎻
      subtitle: '<br>Delong is passionate about music！
      <br>He was awarded a violin performance diploma from the {{< staticref "http://en.ccom.edu.cn/" "newtab" >}}Central Conservatory of Music{{< /staticref >}} (中央音乐学院). 
      <br>He served as the concertmaster of the Hohai University Symphony Orchestra during 2019-2020. 
      <br>He is also at {{< staticref "https://space.bilibili.com/291158396" "newtab" >}}bilibili.com{{< /staticref >}} with 20k+ followers.
      <br><br>
      '
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
      subtitle: '<br>'
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
