---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: 概要
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: 张邦毅
  - block: features
    id: skills
    content:
      title: 技能
      items:
        - name: Java
          description: 
          icon: jee
          icon_pack: custom
        - name: MySQL
          description: 
          icon: mysql
          icon_pack: custom
        - name: MongoDB
          description: 
          icon: mongodb
          icon_pack: custom
        - name: Linux
          description: 
          icon: tux
          icon_pack: custom
        - name: Postman
          description: 
          icon: postman
          icon_pack: custom
        - name: Docker
          description: 
          icon: docker
          icon_pack: custom
        - name: Photoshop
          description: 
          icon: photoshop
          icon_pack: custom
        - name: Office 365
          description: 
          icon: office
          icon_pack: custom
        - name: Xmind
          description: 
          icon: xmind
          icon_pack: custom
  - block: experience
    id: experience
    content:
      title: 工作经历
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: 测试工程师
          company: Xmind Ltd
          company_url: ''
          company_logo: xmind
          location: 深圳
          date_start: '2022-11-14'
          date_end: ''
          description: |2-
              主要职责:

              * 软件质量保证
              * 产品迭代优化
              * 用户反馈处理
        - title: 测试工程师
          company: OnePlus · 实习
          company_url: ''
          company_logo: oneplus
          location: 深圳
          date_start: '2020-06-08'
          date_end: '2020-12-08'
          description: |2-
              主要职责:

              * 软件质量保证
              * 缺陷管理跟踪
    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 证书
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org/account/accomplishments/certificate/26Z62CSLEFNX
          date_end: ''
          date_start: '2023-07-01'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Foundations of User Experience (UX) Design
          url: ''
        - certificate_url: https://www.credly.com/badges/518e5073-0108-4e73-994b-790d1ed2126b/linked_in_profile
          date_end: ''
          date_start: '2023-07-02'
          description: 
          organization: The Linux Foundation
          organization_url: https://training.linuxfoundation.org/
          title: Cybersecurity Fundamentals
          url: 
        - certificate_url: https://www.linkedin.com/learning/certificates/8d44a5b7958748e8caacb936d3f5dab4f5f7ddf975dec745c7b00f8f7913589e?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base%3BQfia4dCnTK%2BhyMc2OzJfFA%3D%3D
          date_end: ''
          date_start: '2023-08-01'
          description: ''
          organization: Microsoft
          organization_url: https://www.linkedin.com/learning/
          title: Career Essentials in Generative AI by Microsoft and LinkedIn
          url: ''
    design:
      columns: '2'
  - block: experience
    id: projects
    content:
      title: 项目经历
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many experience `items` below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Chatmind
          company: Xmind Ltd
          company_url: ''
          company_logo: 
          location: 
          date_start: '2023-08-01'
          date_end: ''
          description: |2-
              * 负责注册登录模块的测试，包括功能测试、用户验证和安全性验证。确保注册登录流程的稳定性和安全性。
              * 深入了解ChatGPT接口，并进行接口的检查和测试。确保ChatGPT与系统的顺利交互和一致性。
              * 根据产品PDR（产品需求文档）进行产品检测，验证系统功能是否满足需求，发现并记录潜在的问题和改进点。
              * 使用测试工具和方法，进行系统的端到端测试，确保系统在各种使用场景下的稳定性和可靠性。
              * 与开发人员、设计人员和产品经理紧密合作，参与产品讨论和讲解，提出意见、建议和改进方案。
              * 根据用户的反馈和测试结果，提供优化和改进建议，并与团队共同推动产品的改进和迭代。
              * Chatmind项目为我提供了深入了解注册登录功能、接口测试以及产品检测的机会。通过与团队合作，我加深了对产品需求的理解，并能够在测试过程中识别和跟踪问题。参与测试和产品改进过程，我得以提出宝贵的意见和建议，对产品的优化发挥了积极的作用。这个项目使我提高了测试技术和沟通协作的能力，并对产品开发过程有了更深入的了解。

        - title: Xmind Works（Xmind Web端）
          company: Xmind Ltd
          company_url: ''
          company_logo: 
          location: 
          date_start: '2022-12-01'
          date_end: ''
          description: |2-
              * 与产品讨论项目特性：在项目开始阶段，我与产品团队进行会议，讨论项目的各项特性和功能。我积极参与讨论，提供测试角度的意见和建议，以确保项目的可测试性和质量。

              * 跟踪网页流量和用户反馈：在项目初期上线后，我负责跟踪网页流量和用户的反馈情况。通过收集和分析用户反馈，我能够了解用户需求和问题，将其作为改进产品和开发新功能的依据。我与产品和开发团队紧密合作，根据流量和用户反馈制定新功能的上线时间表。

              * 参与Collaboration功能上线：在项目发布后，我主要参与了Collaboration功能的测试和上线。这个新功能实现了多用户实时协同编辑文档的操作。我与产品团队进行讨论，共同确定逻辑和测试方案，并参与制定压力测试方案，以确保功能的稳定性和可扩展性。

              * 参与UI升级：在项目的后期阶段，产品重新设计了整个产品的UI，并改变了一些首页的操作逻辑。作为测试工程师，我在设计测试用例的过程中发现了一些问题的逻辑。我积极与产品和开发团队讨论，提出优化的方案和建议，以改善用户体验和产品的可用性。

              * 我在XMind Works项目中积极参与了与产品的讨论、网页流量和用户反馈的跟踪、Collaboration功能的开发与测试，以及UI升级的优化。通过我的努力和专业知识，我为项目的成功提供了全面的测试支持，确保了功能的稳定性和用户体验的持续提升。

        - title: Xmind 桌面端
          company: Xmind Ltd
          company_url: ''
          company_logo: 
          location: 
          date_start: '2022-11-01'
          date_end: ''
          description: |2-
              * 与产品经理对接：积极与产品经理合作，参与需求评审和讨论会议。通过深入了解产品需求，我能够制定相应的测试策略和计划，确保完整地覆盖功能和用户需求。

              * 测试用例编写和执行：我负责编写详细的测试用例，根据产品需求和设计文档进行测试。通过执行测试用例，我能够捕获和报告缺陷，并与开发团队合作验证修复。

              * 缺陷管理：我使用缺陷跟踪工具来记录、追踪和管理产品中发现的问题。我提供准确和有用的缺陷报告，包括重现步骤、环境信息和截图，以帮助开发团队快速定位和解决问题。

              * 测试执行和结果分析：我执行各种测试类型，如功能测试、界面测试、兼容性测试等，以验证产品的稳定性和一致性。通过仔细分析测试结果，我能够识别潜在问题，并提供改进意见和建议。

              * 与技术支持团队合作：我与技术支持团队紧密合作，以了解用户反馈和问题。我协助解决和解释与产品质量相关的问题，并与开发团队沟通，确保问题得到及时解决。

              * 通过我在测试用例编写和执行、缺陷管理、测试执行和结果分析，以及与产品经理和技术支持团队的紧密合作，我展现了我的产品能力，并致力于提供高品质的产品和卓越的用户体验。
        - title: 谷歌拨号APP通话录音功能 (由 Oxygen OS 定制)
          company: OnePlus
          company_url: ''
          company_logo: 
          location: 
          date_start: '2020-06-01'
          date_end: '2020-12-01'
          description: |2-
              * 仔细地分析了通话录音功能的需求文档，并熟练地进行了严格的测试和测试用例编写。
              * 实现了95%的测试用例覆盖率，证明了高水平的系统测试能力。
              * 对细节异常警觉，项目的错误检测率一直保持在3%以下。
              * 上线后展示出卓越的问题跟踪和解决能力，快速识别和复现问题，并提供可靠的反馈及积极解决问题。
  - block: contact
    id: contact
    content:
      title: 联系
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: cheungbunngai@gmail.com
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      address:
        street: 
        city: 粤港澳大湾区
        region: 中国
        postcode: 
        country: 中国
        country_code: CN
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      contact_links:
        - icon: telegram
          icon_pack: fab
          name: 通过 Telegram 联系我
          link: 'https://twitter.com/Twitter'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: 
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
