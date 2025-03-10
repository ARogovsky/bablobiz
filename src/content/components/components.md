---
draft: false
contactform:
 formAction: "https://api.web3forms.com/submit"
 accessKey: "YOUR_ACCESS_KEY_HERE"
 fields:
   - name: "Full Name"
     type: "text"
     required: true
     placeholder: "Full Name"
     feedback: "Please provide your full name."
   - name: "Email Address"
     type: "email"
     required: true
     placeholder: "Email Address"
     feedback:
       empty: "Please provide your email address."
       invalid: "Please provide a valid email address."
   - name: "Message"
     type: "textarea"
     required: true
     placeholder: "Your Message"
     feedback: "Please enter your message."
 button:
   text: "Send Message"
   size: "lg"
   block: true
 resultId: "result"
 feedbackTimeout: 5000
cta:
 title: "Optimize your business leads with AI"
 description: "Leverage Business AI to better assist your team and optimize lead conversion with cutting-edge tools."
 button:
   text: "Demo"
   href: "/demo/"
   style: "inverted"
features:
 title: "Why Choose BABLO?"
 description: "BABLO provides AI-powered solutions to analyze calls, train managers, and enhance lead optimization."
 items:
   - title: "AI-Driven Call Analytics"
     description: "Leverage AI to analyze call quality, extract insights, and improve performance."
     icon: "simple-icons:openai"
   - title: "Manager Training"
     description: "Provide managers with actionable insights to refine their negotiation and leadership skills."
     icon: "simple-icons:microsoftteams"
   - title: "Enhanced Lead Optimization"
     description: "Optimize your business leads with intelligent prioritization and AI-powered recommendations."
     icon: "simple-icons:googleanalytics"
   - title: "Scalable Integrations"
     description: "Seamlessly integrate BABLO with your existing CRM, telephony, and analytics tools."
     icon: "simple-icons:salesforce"
   - title: "Real-Time Insights"
     description: "Monitor performance and make informed decisions with live data dashboards."
     icon: "simple-icons:grafana"
   - title: "AI-Powered Assistance"
     description: "Provide your team with an AI-driven assistant to improve workflow and communication."
     icon: "simple-icons:microsoft"
footer:
 text: "Copyright © {year} BABLO.biz. All rights reserved."
 credits:
   text: "Powered by BABLO AI Solutions"
   url: "https://bablo.biz"
hero:
 title: "Transform Your Business with BABLO"
 description: "Business AI – Better Assistant for Leads Optimization. Enhance call analytics, train managers, and drive results with AI."
 buttons:
   - text: "Try Now"
     href: "/demo"
     icon: "bx:bxs-rocket"
     style: "primary"
   - text: "Contact Us"
     href: "/contact"
     icon: "bx:bxs-envelope"
     style: "outline"
 heroImage: "../assets/hero.png"
logos:
 title: "Trusted by Top Technologies"
 logos:
   - "simple-icons:openai"
   - "simple-icons:salesforce"
   - "simple-icons:googleanalytics"
   - "simple-icons:grafana"
   - "simple-icons:microsoft"
sectionhead:
 defaultTitle: "Your AI-Powered Advantage"
 defaultDescription: "Unlock the full potential of AI for your business operations."
navbar:
 brand:
   name: "BABLO"
   logo: "/"
 menuitems:
   - title: "Try Now"
     path: "/demo"
     badge: "Free"
   - title: "About"
     path: "/about"
   - title: "Blog"
     path: "/blog"
   - title: "Contact"
     path: "/contact"
---
