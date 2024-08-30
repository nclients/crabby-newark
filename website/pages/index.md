---
# Do not change the content below
layout: "ssg-theme-astro/layouts/main.astro"
tag: "GTM-MJ592KWF"
title: "CRABBY CRABBY NEWARK - Best Food Today"
favicon: "favicon.ico"
logo: "logo.png"
primaryColor: "#FF2D2F" # logo color
secondaryColor: "#ffffff"
primaryColorScheme: "dark" # dark | light
secondaryColorScheme: "light"
dataGlfCuid: ""
dataGlfRuid: ""
orderOnlineLink: "https://www.bestfoodtodayus.com/ordering/restaurant/menu?restaurant_uid=c14b3f12-00e9-43ef-aef3-9716b42c8c34"
tableReservationLink: ""
tel: "510-588-1218"

banner:
  text: 
    - boldText: "🥳 Lunch Specials"
    - text: "0.5 lb Head On Shrimp, 0.5 lb Green Mussels, 1 corn 2 potatoes 4 pc sausages. Only $12.99. Available Monday to Friday, 11:30 AM to 3 PM."
    # - smText: "(Steam Rice (10 oz cup) / Garlic Noodles (10 oz cup) / Cajun Fries
    #           (10 oz cup))."
    # - text: " Only $13.50. Available Monday to Friday, 11:30 AM to 3 PM."
  # add more text...
  textColor: "#ffffff"
  bgColor: "#FF2D2F"
  bgOpacity: "1" # 0~1

# header
header:
  logoSize: 55
  textAfterLogo: 
    text: ""
    size: 16
    color: ""
  bgColor: "#000000"
  bgOpacity: "0.8" # 0~1
  menuTextColor: "#ffffff"
  menu:
    - { text: "Home", link: "/" }
    - { text: "Gallery", link: "#gallery" }
    - { text: "About Us", link: "#about-us" }
    - { text: "Contact Us", link: "#contact-us" }
    - { text: "中文", link: "/zh-cn" }
  addOrderOnlineBtn: false
  orderOnlineBtnInsteadText: ""
  addTableReservationBtn: false
  tableReservationBtnInsteadText: ""
  addTelBtn: true
  telTextColor: "#ffffff"
  addOtherBtn: true
  otherBtnInsteadText: "See MENU & Order"
  otherBtnHref: "https://www.bestfoodtodayus.com/ordering/restaurant/menu?restaurant_uid=c14b3f12-00e9-43ef-aef3-9716b42c8c34"

sections:


# hero
  - type: "hero" 
    id: ""
    height: "100" # Conditionally use only when sectionType is imgBg
    sectionType: "video" # video | imgWithText | imgBg
    bgVideoType: "gjw" # youtube | vimeo | gjw
    bgVideoId: "1gvlm41386a7H97kaPJg4V9Gh18o1c"
    bgImg: "crabby_crabby_newark_hero_background_image.webp"
    bgImgAlt: "crabby crabby newark Hero Background Image"
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "Crabby Crabby Newark"
    titleColor: "#ffffff"
    description: 
      - "Delight your Palate, Discover your Smile at Crabby Crabby."
    descriptionColor: "#ffffff"

    addOrderOnlineBtn: false
    orderOnlineBtnInsteadText: "See MENU & Order"
    addTableReservationBtn: false
    tableReservationBtnInsteadText: ""
    showOtherBtn: true
    btn1Text: "See MENU & Order" # default: order online
    btn1Href: "https://www.bestfoodtodayus.com/ordering/restaurant/menu?restaurant_uid=c14b3f12-00e9-43ef-aef3-9716b42c8c34" # default: order online
    btn2Text: "" # default: table reservation
    btn2Href: "" # default: table reservation

    bannerImg: "crabby_crabby_newark_dish.webp"
    imgAlt: "Crabby Crabby Newark "
    imgPosition: "imgLeft" # imgLeft | imgRight
    bannerMarginTopMobile: 12
    imgRounded: "lg" # sm | md | lg | xl | 2xl | 3xl | full
   
    bottomRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full
    # bottomInfo: "We offer Takeout"

# Video
  - type: "video"
    id: ""
    title: 
      - "A Corner of Tradition and Flavor"
    description: 
      - "From the heart of Newark, CA, Crabby Crabby Restaurant is a corner where tradition meets flavor. Every corner of our restaurant is infused with authenticity, from the décor to every bite we serve." 
    videoType: "gjw" # vimeo | gjw | youtube
    videoId: 
      - "1gq2biogr2i6gHN3AizUEgler1ug1c"
      - "1go20iea10u7ATj8Hyv9zPYCF19j1c"
    isOnlyDisplayOnMobile: false

# Gallery  
  - type: "gallery"
    id: "gallery"
    mode: 3 # 1 - 3
    bgImg: ""
    bgImgAlt: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "Food At Crabby Crabby Newark"
    titleColor: "#000000"
    description: 
      - "This is the best place to find delicious seafood."
    descriptionColor: "#333333"
    folderPath: "gallery"
    showImgName: true # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full


# # textBlock 
#   - type: "textBlock" 
#     id: "about-us"
#     bgImg: ""
#     bgImgAlt: ""
#     bgColor: "#000"
#     bgOpacity: "" # 0~1
    # title: 
    #   - "A Corner of Tradition and Flavor"
    # titleColor: "#000000"
    # description: 
    #   - "From the heart of Newark, CA, Crabby Crabby Restaurant is a corner where tradition meets flavor. Every corner of our restaurant is infused with authenticity, from the décor to every bite we serve."
    #   # - text: "We serve Imperial Soup dishes plus other Asian dishes. Feel free to message us about inquiries! We'll get back to you as soon as we can!"
    # descriptionColor: "#000000"

# textBlock - only title
  - type: "textBlock" 
    id: "about-us"
    bgImg: ""
    bgImgAlt: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "About Us"
    titleColor: "#000000"
    description: 
      - ""
    descriptionColor: ""

# feature - 2
  - type: "feature" 
    id: ""
    height: "100" # Conditionally use only when sectionType is imgBg
    noMarginTop: "all" # mobile | tablet | desktop ｜ all
    sectionType: "imgWithText" # video | imgWithText | imgBg
    bgVideoType: "" # youtube | vimeo | gjw
    bgVideoId: ""
    bgImg: ""
    bgImgAlt: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "Our Mission"
    titleColor: "#000000"
    description: 
      - "At Crabby Crabby Restaurant, our mission is simple yet powerful: to pursue culinary excellence in every detail. We strive to deliver an exceptional dining experience that delights the senses and creates lasting memories for our customers."
    descriptionColor: "#000000"
    # title2: 
    #   - "A Corner of Tradition and Flavor"
    # title2Color: "#000000"
    # description2: 
    #   - "From the heart of Newark, CA, Crabby Crabby Restaurant is a corner where tradition meets flavor. Every corner of our restaurant is infused with authenticity, from the décor to every bite we serve."
    #   # - text: "We serve Imperial Soup dishes plus other Asian dishes. Feel free to message us about inquiries! We'll get back to you as soon as we can!"
    # description2Color: "#000000"
    # title2: 
    #   - "Committed to the Community"
    # title2Color: "#000000"
    # description2: 
    #   - "We are proud to be an active part of the Newark, CA community. Through special events, collaborations with local venues and participation in community initiatives, Crabby Crabby Restaurant seeks to strengthen the ties that bind us together."
    # description2Color: "#000000"
    isTextAlignCenter: false

    addOrderOnlineBtn: false
    orderOnlineBtnInsteadText: "See MENU & Order"
    addTableReservationBtn: false
    tableReservationBtnInsteadText: ""
    showOtherBtn: false
    btn1Text: "See MENU & Order" # default: order online
    btn1Href: "https://www.bestfoodtodayus.com/ordering/restaurant/menu?restaurant_uid=c14b3f12-00e9-43ef-aef3-9716b42c8c34" # default: order online
    btn2Text: "" # default: table reservation
    btn2Href: "" # default: table reservation

    bannerImg: "crabby_crabby_newark_exterior.webp"
    imgAlt: "crabby crabby newark exterior"
    imgPosition: "imgLeft" # imgLeft | imgRight
   
    bottomRounded: "" # sm | md | lg | xl | 2xl | 3xl | full


# feature - 3
  - type: "feature" 
    id: ""
    height: "100" # Conditionally use only when sectionType is imgBg
    sectionType: "imgWithText" # video | imgWithText | imgBg
    bgVideoType: "" # youtube | vimeo | gjw
    bgVideoId: ""
    bgImg: ""
    bgImgAlt: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "Committed to the Community"
    titleColor: "#000000"
    description: 
      - "We are proud to be an active part of the Newark, CA community. Through special events, collaborations with local venues and participation in community initiatives, Crabby Crabby Restaurant seeks to strengthen the ties that bind us together."
    descriptionColor: "#000000"

    addOrderOnlineBtn: false
    orderOnlineBtnInsteadText: "See MENU & Order"
    addTableReservationBtn: false
    tableReservationBtnInsteadText: ""
    showOtherBtn: false
    btn1Text: "See MENU & Order" # default: order online
    btn1Href: "https://www.bestfoodtodayus.com/ordering/restaurant/menu?restaurant_uid=c14b3f12-00e9-43ef-aef3-9716b42c8c34" # default: order online
    btn2Text: "" # default: table reservation
    btn2Href: "" # default: table reservation

    bannerImg: "handwritten_menu.webp"
    imgAlt: "Crabby Crabby Newark "
    imgPosition: "imgRight" # imgLeft | imgRight
   
    bottomRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

# textBlock - Information
  - type: "textBlock" 
    id: ""
    bgImg: "/gallery/Tacos_2.webp"
    bgImgAlt: "Crabby Crabby Newark - Best Food Today"
    bgColor: "#000"
    bgOpacity: "0.6" # 0~1
    title: 
      - "NEW! Online Ordering"
    titleColor: "#ffffff"
    description: 
      - "Online ordering NOW enabled for pick-up. Just tell us what you want and we'll prepare it as fast as we can. All orders are manually confirmed by us directly. Find out in real-time when your food is ready. All orders are manually confirmed by us in real-time. Watch on-screen when your food is ready for pickup."
    descriptionColor: "#ffffff"
  
# map  
  - type: "map"
    id: "contact-us"
    noMarginTop: true
    mode: "fullWidth" # full-width | ...
    url: "https://maps.app.goo.gl/gHferfbrQsJXDHNX9"
    iframeUrl: "https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3163.2010723950107!2d-122.05385532436703!3d37.55032622505781!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808fbf25977c4139%3A0x65a0766c424ad6dc!2sCrabby%20Crabby%20Newark!5e0!3m2!1sen!2sjp!4v1721832800644!5m2!1sen!2sjp"
    addTelBtn: true
    getDirectionBtnInsteadText: ""
    telInsteadText: "Tel: 510-588-1218"
 
  # - type: "modal"
  #   bgColor: "#333"
  #   bgOpacity: "0.1" # 0~1
  #   title: 
  #     - "🥳 Special Offers"
  #   titleColor: "#FF2D2F"
  #   titleSize: 24
  #   description: 
  #     - ""
  #   descriptionColor: ""
  #   descriptionSize: 16
  #   imgName: "offer.png"
  #   imgAlt: "🥳 Special Offer 15 PC of Head On Shrimp + 1 Free Soda + Choose a Free Item: Steam Rice (10 oz cup) / Garlic Noodles (10 oz cup) / Cajun Fries (10 oz cup) only $13.50. Available Monday to Friday, 12 PM to 3 PM."
  #   buttonText: "Order Now!"

footer:
  mode: 1 # 1
  noMarginTop: true
  bgImg: "dedicated_to_gastronomic_excellence.webp"
  bgImgAlt: "Crabby Crabby Newark - Best Food Today"
  bgColor: "#000000"
  bgOpacity: "0.65" # 0~1
  openingHours: 
    - "Monday to Friday:"
    - "Lunch 11:30 AM to 3:00 PM, Dinner 5:00 PM to 9:00 PM"
    - "Saturday and Sunday:"
    - "12:00 PM to 9:00 PM"
  menu:
    - { text: "Home", link: "/" }
    - { text: "Gallery", link: "#gallery" }
    - { text: "About Us", link: "https://crabbynewark.com/#about-us" }
    - { text: "Contact Us", link: "https://crabbynewark.com/#contact-us" }
    - { text: "中文", link: "/zh-cn" }

  FB: true
  FBLink: "https://www.facebook.com/CrabbyCrabbyNewarkMX/"
  IG: true
  IGLink: "https://www.instagram.com/crabbycrabby3ca?igsh=a3VqdW81b25hNDR1"
  X: false
  XLink: ""
  youtube: false
  youtubeLink: ""
  yelp: false
  yelpLink: ""
  paymentMethod: "cash,visa" #alipay,applePay,cash,discover,googlePay,jcb,maestro,mastercard,stripe,unionPay,visa,weChatPay,payPal

seo:
  metaTitle: "" 

  metaDescription: "Crabby Crabby Newark is a premier seafood restaurant located at 6225 Jarvis Ave, Newark, CA 94560. Enjoy fresh and delicious seafood dishes in a vibrant and friendly atmosphere."

  keywords: "" # steak, restaurant, fine dining, New York

  img: "https://crabbynewark.com/gallery/Seafood_Whole_Dungeness_Crab.webp" # https://example.com/photos/1x1/photo.jpg

  thisPageUrl: "https://crabbynewark.com/" # https://example.com/

  locale: "en_US" # zh_TW | zh_CN | ja_JP

  canonicalHref: "https://crabbynewark.com/" # https://example.com/

  name: "Crabby Crabby Newark" # restaurant name

  images:
    - "https://crabbynewark.com/gallery/Seafood_Whole_Dungeness_Crab.webp"  # https://example.com/photos/1x1/photo.jpg
    - "https://crabbynewark.com/gallery/Tacos_2.webp"  # https://example.com/photos/1x1/photo.jpg
    - "https://crabbynewark.com/gallery/Seafood_Whole_Dungeness_Crab_2.webp"  # https://example.com/photos/1x1/photo.jpg
    - 
  address:
    streetAddress: "6225 Jarvis Ave" # 148 W 51st St
    addressLocality: "Newark" # New York
    addressRegion: "CA" # NY
    postalCode: "94560" # 10019
    addressCountry: "US" # US


  review:
    ratingValue: "4.5" #4.5
    bestRating: "5" # 5
    authorName: "Google Review" # Google Review
    reviewType: "Organization" # Organization. Google Review ->"Organization", 

  # review:
  #   ratingValue: "4.5"
  #   bestRating: "5"
  #   authorName: "Yelp"
  #   reviewType: "Organization" # Yelp 是一个组织，因此设置为 Organization

  # review:
  #   ratingValue: "4.9"
  #   bestRating: "5"
  #   authorName: "John Doe"
  #   reviewType: "Person"


  geo:
    latitude: 37.55052611620485 # 40.761293
    longitude: -122.0512589463209 # -73.982294
  url: "https://crabbynewark.com/" # https://www.example.com
 
  telephone: "+1-510-588-1218" # +1212345678

  servesCuisine: [
    "Seafood",
    "Cajun Cuisine",
    "American Cuisine"
]
  priceRange: "$$" # $,$$,$$$,$$$$. $->Inexpensive, $$->Moderate, $$$->Expensive, $$$$->Luxury
  openingHours:
  - dayOfWeek:
      - "Monday"
      - "Tuesday"
      - "Wednesday"
      - "Thursday"
      - "Friday"
    opens: "11:30"
    closes: "15:00"
  - dayOfWeek:
      - "Monday"
      - "Tuesday"
      - "Wednesday"
      - "Thursday"
      - "Friday"
    opens: "17:00"
    closes: "21:00"
  - dayOfWeek:
      - "Saturday"
      - "Sunday"
    opens: "12:00"
    closes: "21:00"
   
  menu: "https://crabbynewark.com/" # https://example.com/
  # acceptsReservations: true # true or false
  hasMenu: "https://crabbynewark.com/" # https://crabbynewark.com/full-menu
  starRating:
    ratingValue: "4.5" # 4.5
    bestRating: "5" # 5
    author: "Google Review" # Michelin Guide, Google Review
    authorType: "organization" #person,organization
  currenciesAccepted: "USD" # USD
  paymentAccepted: "Cash, Visa"

  hasMenuSection:
    - name: "SEAFOOD" # Appetizers
      image: "https://crabbynewark.com/gallery/Seafood_Whole_Lobster.webp"
      description: "From the heart of Newark, CA, Crabby Crabby Restaurant is a corner where tradition meets flavor."
      hasMenuItem:
        - name: "Half Pound Snow Crab"
          description: "Succulent half pound of snow crab, expertly prepared for a delightful dining experience."
          price: "20.50"
          image: "https://crabbynewark.com/gallery/Seafood_Half_Pound_Snow_Crab.webp"
        - name: "Whole Lobster"
          description: "Savor the taste of our whole lobster, cooked to perfection and bursting with flavor."
          price: "52.99"
          image: "https://crabbynewark.com/gallery/Seafood_Whole_Lobster.webp"
    - name: "Combo" # Main Courses
      hasMenuItem:
        - name: "Combo Deal #1"
          description: "1lb Head On Shrimp, 1lb Crawfish Or Clams, 1lb Green Mussels. Pick 2 Free Items:1 Corn Or 2 Potatoes Or 4 Pc of Sausages."
          price: "45.00"
          image: ""
        - name: "Combo Deal #2"
          description: "1lb King Crab Legs, 1lb Head On Shrimp, 1lb Crawfish Or Clams. Pick 3 Free Items: 1 Corn Or 2 Potatoes Or 4 Pc of Sausages."
          price: "80.00"
          image: ""
    - name: "Lunch Specials" # Appetizers
      hasMenuItem:
        - name: "Lunch Special #1"
          description: "0.5 lb Head On Shrimp, 0.5 lb Black Mussels"
          price: "12.99"
          image: ""
        - name: "Lunch Special #2"
          description: "0.5 lb Head On Shrimp, 0.5 lb Green Mussels"
          price: "12.99"
          image: ""
    - name: "Fried" # Main Courses
      # description: "Each Selection Made To Order,Hand-Tossed In Our Secret Batter."
      image: "https://crabbynewark.com/gallery/Fried_Calamari_W_Fries.webp"
      hasMenuItem:
        - name: "Fried Calamari W Fries"
          description: "Crispy calamari served with golden fries, perfect for sharing or indulging on your own."
          price: "12.99"
          image: "https://crabbynewark.com/gallery/Fried_Calamari_W_Fries.webp"
        # - name: "S1 水煮鱼片 Sichuan Poached Spicy Fish Filet"
        #   description: "Spicy poached fish fillet in Sichuan style."
        #   price: "12.99"
        #   image: ""
        
  offers:
    - name: "Lunch Specials"
      description: "0.5 lb Head On Shrimp, 0.5 lb Black Mussels, 1 corn 2 potatoes 4 pc sausages. Only $12.99. Available Monday to Friday, 11:30 AM to 3 PM."
      priceCurrency: "USD"
      price: "12.99"
      # image: "https://crabbynewark.com/offer.png"
    # - name: "10% off cash discount on family meal takeout"
    #   description: "Get 10% off when you pay with cash for family meal takeout."
    #   priceCurrency: "USD"
    #   price: "varies"
    #   image: ""
    # - name: "Family Set: Any 3 dishes for $40"
    #   description: "Choose any 3 dishes for just $40, includes free rice."
    #   priceCurrency: "USD"
    #   price: "40"
    #   image: ""
    # - name: "Free rice with lunch"
    #   description: "Receive free rice with any lunch order."
    #   priceCurrency: "USD"
    #   price: "0"
    #   image: ""
      
---
<!-- Powered by Best Food Today -->
---
