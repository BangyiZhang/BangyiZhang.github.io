---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Summary
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    id: skills
    content:
      title: Skills
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
        - title: Test Engenieer
          company: Xmind Ltd
          company_url: ''
          company_logo: xmind
          location: Shenzhen
          date_start: '2022-11-14'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Quality Assurance
              * Product Optimization
              * Feedback Handling
        - title: Test Engenieer
          company: OnePlus · Intern
          company_url: ''
          company_logo: oneplus
          location: Shenzhen
          date_start: '2020-06-08'
          date_end: '2020-12-08'
          description: |2-
              Responsibilities include:

              * Quality Assurance
              * Bug Tracking
    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
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
      title: Project Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
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
              * Responsible for testing the registration and login module, including functional testing, user verification, and security validation. Ensured the stability and security of the registration and login process.
              * Deeply familiarized with the ChatGPT interface and performed interface checks and testing. Ensured smooth interaction and consistency between ChatGPT and the system.
              * Conducted product testing based on the Product Design Requirements (PDR), verifying if the system's functionalities meet the requirements, and identified potential issues and improvement points.
              * Utilized testing tools and methods to perform end-to-end testing of the system, ensuring stability and reliability in various usage scenarios.
              * Collaborated closely with developers, designers, and product managers, actively participated in product discussions and presentations, and provided suggestions, feedback, and improvement proposals.
              * Provided optimization and improvement suggestions based on user feedback and test results, and worked collaboratively with the team to drive product enhancements and iterations.
              * The Chatmind project provided me with an opportunity to gain in-depth knowledge of testing registration and login functionalities, interface testing, and product evaluation. Through collaboration with the team, I deepened my understanding of product requirements and became proficient in identifying and tracking issues during the testing process. Participating in the testing and product improvement process allowed me to provide valuable feedback and suggestions, positively influencing product optimization. This project enhanced my testing skills, as well as my ability to communicate and collaborate effectively, while providing me with insights into the product development process.
        - title: Xmind Works
          company: Xmind Ltd
          company_url: ''
          company_logo: 
          location: 
          date_start: '2022-12-01'
          date_end: ''
          description: |2-
              * Engaged in collaborative discussions with the product team to define project features and functionalities at the project inception stage. Provided valuable testing insights and recommendations to ensure project testability and quality.

              * Tracked web traffic and gathered user feedback to gain insights into user needs and issues. Utilized collected data to drive product improvements and new feature development. Collaborated closely with the product and development teams to establish deployment timelines based on traffic and user feedback.

              * Contributed extensively to the development and testing of the Collaboration feature post-project launch. Collaborated with the product team to define feature logic and testing strategies. Actively participated in formulating stress testing approaches to ensure feature stability and scalability.

              * Played a key role in the UI upgrade phase, contributing to identifying logic issues during the test case design process. Actively collaborated with the product and development teams to propose optimization solutions and suggestions for enhancing user experience and product usability.

              * Contributed actively to XMind Works project through productive collaboration with the product team, diligent tracking of web traffic and user feedback, active involvement in the development and testing of the Collaboration feature, and proactive optimization of UI upgrades. Demonstrated comprehensive testing support, ensuring feature stability and continuous enhancement of user experience, leading to project success.
        - title: Xmind Desktop
          company: Xmind Ltd
          company_url: ''
          company_logo: 
          location: 
          date_start: '2022-11-01'
          date_end: ''
          description: |2-
              * Collaborated effectively with Product Managers to ensure alignment on requirements and participate in requirement reviews and discussion meetings. Developed thorough understanding of product needs to devise comprehensive testing strategies and plans. Ensured complete coverage of functionalities and user requirements. 

              * Developed and executed detailed test cases based on product requirements and design documents. Identified and reported defects, working closely with the development team to validate fixes. 

              * Utilized defect tracking tools to record, track, and manage product issues. Provided accurate and informative defect reports, including reproducible steps, environment details, and screenshots. Facilitated efficient problem resolution by enabling the development team to quickly locate and address issues. 

              * Conducted various types of testing, such as functional testing, interface testing, and compatibility testing, to ensure product stability and consistency. Analyzed test results meticulously to identify potential issues and provided valuable insights and recommendations. 

              * Collaborated closely with the Technical Support team, actively engaging in user feedback analysis and issue resolution. Assisted in addressing quality-related concerns and effectively communicated with the development team to ensure prompt problem solving. 

              * Through my expertise in test case development and execution, defect management, test execution and result analysis, and collaborative approach with Product Managers and Technical Support teams, I have consistently delivered high-quality products and outstanding user experiences. 
        - title: Google Phone Call Recording Feature (OxygenOS Customization)
          company: OnePlus
          company_url: ''
          company_logo: 
          location: 
          date_start: '2020-06-01'
          date_end: '2020-12-01'
          description: |2-
              * Diligently analyzed the call recording feature's requirement document and skillfully conducted rigorous testing and test case writing.
              * Demonstrated a high level of testing proficiency through multiple rounds of system testing, achieving an impressive 95% test case coverage.
              * The project's bug detection rate remained under the 3% threshold thanks to vigilant attention to detail.
              * Showcased exceptional post-launch issue tracking skills, quickly identifying and reproducing problems, offering reliable feedback, and proactively working to resolve issues.
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: cheungbunngai@gmail.com
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      address:
        street: 
        city: The Greater Bay Area
        region: CN
        postcode: 
        country: China
        country_code: CN
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      contact_links:
        - icon: telegram
          icon_pack: fab
          name: DM Me
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
