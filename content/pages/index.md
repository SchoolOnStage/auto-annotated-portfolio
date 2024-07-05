---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: Wicked Jazz jam
    subtitle: DJ & friends
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
    text: >
      Grooven funken en jammen op de meest smaakvolle quotes van jazz, funk, hip
      hop, disco, soul, electronica, afro, breaks, house, drum\&bass, latin en
      pop. DJ & Gitarist Marco Tenkink maakt met muzikale gasten van iedere plek
      een mini festival
    media:
      type: VideoBlock
      title: WickedJazzJam
      url: 'https://youtu.be/OT7eswYnHGA'
      elementId: ''
      autoplay: false
      loop: false
      muted: false
      controls: true
      aspectRatio: '16:9'
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Featured Posts
    showFeaturedImage: false
    actions: []
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
---
