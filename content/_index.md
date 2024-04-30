---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-04-30
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: publication
    content:
      title: Featured Publications
      text: |-
        {{% callout note %}}
        Browse all publications [here](publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        featured_only: true
      count: 3
    design:
      columns: '2'
      view: card
  - block: experience
    id: experience
    design:
      columns: '2'
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006 

      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: "Researcher"
          company: "NTT Communication Science Laboratories"
          date_start: "2020-04-01"
          date_end: "" 
          location: Kyoto, Japan
          description: ""

        - title: "Ph.D. Student"
          company: "Nara Institute of Science and Technology"
          date_start: "2023-04-01"
          date_end: ""
          location: Nara, Japan
          description: ""

        - title: "M.Eng. Student"
          company: "Nara Institute of Science and Technology"
          date_start: "2018-04-01"
          date_end: "2020-03-31"
          location: Nara, Japan
          description: |2- 
            M.Eng. student in Augmented Human Communication Laboratory, Department of Information Science, Nara Institute of Science and Technology.
            Research for Neural Machine Translation, supervised by Prof. Satoshi Nakamura and Prof. Katsuhito Sudoh.

        - title: "B.Eng. Student"
          company: "Osaka Prefecture University College of Technology"
          date_start: "2016-04-01"
          date_end: "2018-03-31"
          location: "Osaka, Japan"
          description: |2-
            B.Eng. student in Advanced Cource, Osaka Prefecture University College of Technology.
            Research for Image Question Answering, supervised by Prof. Masanari Kubota.

        - title: "Researcher"
          company: "Nara Institute of Science and Technology"
          date_start: "2019-04-01"
          date_end: "2020-03-31"
          location: "Nara, Japan"
          description: "Working at Data Science Center, Nara Institute of Science and Technology."

        - title: "Internship"
          company: "NTT Communication Science Laboratories"
          date_start: "2018-08-06"
          date_end: "2019-05-31"
          location: "Kyoto, Japan"
          description: ""

        - title: "Internship"
          company: "Cookpad Inc."
          date_start: "2018-08-20"
          date_end: "2018-08-24"
          location: "Tokyo, Japan"
          description: "1 week reseach internship"

        - title: "Researcher"
          company: "Nara Institute of Science and Technology"
          date_start: "2017-11-01"
          date_end: "2018-03-31"
          location: "Nara, Japan"
          description: "Working at Augmented Human Communication Laboratory, Department of Information Science, Nara Institute of Science and Technology."

        - title: "Internship"
          company: "Nara Institute of Science and Technology"
          date_start: "2016-08-01"
          date_end: "2016-09-30"
          location: "Nara, Japan"
          description: |2-
            Internship at Augmented Human Communication Laboratory, Department of Information Science, Nara Institute of Science and Technology.
            Research for Simultaneous Machine Translation between English and Japanese.

        - title: "Internship"
          company: "OPTiM"
          date_start: "2014-08-18"
          date_end: "2014-08-29"
          location: "Tokyo, Japan"
          description: "2 weeks internship"

  - block: accomplishments
    id: achievement 
    design:
      columns: '2'
      view: card
    content:
      title: Achievements
      date_format: Jan 2006
      items:
        - organization: Nara Institute of Science and Technology
          organization_url: http://www.naist.jp/
          title: The Best Student Award
          url: ""
          certificate_url: ""
          date_start: 2020-03-24
          date_end: ""
          description: ""

        - organization: Foundation of Nara Institute of Science and Technology
          organization_url: http://www.science-plaza.or.jp/
          title: NAIST The Best Student Award
          url: ""
          certificate_url: ""
          date_start: 2020-03-24
          date_end: ""
          description: ""

        - organization: SIG-NL, IPSJ
          organization_url: https://nl-ipsj.or.jp/
          title: Young Award
          url: https://nl-ipsj.or.jp/young-award/
          certificate_url: ""
          date_start: 2019-08-31
          date_end: ""
          description: "帖佐 克己, 須藤 克仁, 中村 哲 - 英日同時翻訳のためのConnectionist Temporal Classificationを用いたニューラル機械翻訳"

        - organization: 電気学会 関西支部 第23回高専卒業研究発表会
          organization_url: https://www.iee.jp/kansai/
          title: The Presentation Award
          url: ""
          certificate_url: ""
          date_start: 2016-03-31
          date_end: ""
          description: "帖佐 克己, 窪田 哲也 - 深層学習を用いた話者認識"

        - organization: Supercomputing Contest (SuperCon) 2012
          organization_url: https://www.gsic.titech.ac.jp/supercon/main/attwiki/index.php?Supercomputing%20Contest
          title: 5th Place, IEICE Supercomputing Award, IPSJ Excellent Student Award
          url: ""
          certificate_url: ""
          date_start: 2012-08-01
          date_end: ""
          description: ""

        - organization: Supercomputing Contest (SuperCon) 2011
          organization_url: https://www.gsic.titech.ac.jp/supercon/main/attwiki/index.php?Supercomputing%20Contest
          title: 6th Place
          url: ""
          certificate_url: ""
          date_start: 2011-08-01
          date_end: ""
          description: ""

        - organization: パソコン甲子園2013
          organization_url: https://web-ext.u-aizu.ac.jp/pc-concours/
          title: 8th Place
          url: ""
          certificate_url: ""
          date_start: 2013-11-01
          date_end: ""
          description: ""

        - organization: パソコン甲子園2012
          organization_url: https://web-ext.u-aizu.ac.jp/pc-concours/
          title: 4th Place
          url: ""
          certificate_url: ""
          date_start: 2012-11-01
          date_end: ""
          description: ""

        - organization: パソコン甲子園2011
          organization_url: https://web-ext.u-aizu.ac.jp/pc-concours/
          title: Advanced to the final
          url: ""
          certificate_url: ""
          date_start: 2011-11-01
          date_end: ""
          description: ""

        - organization: 12th Japanese Olympiad in Informatics (第12回日本情報オリンピック)
          organization_url: https://www.ioi-jp.org/
          title: Achieved A rank in qual and final, joined the spring training camp
          url: ""
          certificate_url: ""
          date_start: 2012-12-01
          date_end: 2013-03-31
          description: ""

        - organization: 28th College of Technology Programming Contest (第28回高専プロコン)
          organization_url: http://www.procon.gr.jp/
          title: 2nd Place, NAPROCK First Runner Up Prize
          url: ""
          certificate_url: ""
          date_start: 2017-10-01
          date_end: ""
          description: ""

        - organization: 26th College of Technology Programming Contest (第26回高専プロコン)
          organization_url: http://www.procon.gr.jp/
          title: "7th Place, Jury Prize"
          url: ""
          certificate_url: ""
          date_start: 2016-10-01
          date_end: ""
          description: ""

        - organization: 25th College of Technology Programming Contest (第25回高専プロコン)
          organization_url: http://www.procon.gr.jp/
          title: "Winner"
          url: ""
          certificate_url: ""
          date_start: 2015-10-01
          date_end: ""
          description: |2-
            awarded following prizes:
              * NAPROCK First Runner Up Prize
              * Prize of Minister of Education, Culture, Sports, Science and Technology
              * IPSJ Excellent Student Award
              * BCN IT Junior Award

        - organization: ACM-ICPC 2018
          organization_url: ""
          title: 33th grade in Asia Yokohama Regional Contest
          url: ""
          certificate_url: ""
          date_start: 2018-12-08
          date_end: 2018-12-10
          description: ""

        - organization: ACM-ICPC 2014
          organization_url: ""
          title: 53th grade in Asia Taichung Regional Contest
          url: ""
          certificate_url: ""
          date_start: 2014-11-23
          date_end: ""
          description: ""

---
