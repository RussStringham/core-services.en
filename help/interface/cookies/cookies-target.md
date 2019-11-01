---
description: Target uses cookies to give website operators the ability to test which online content and offers are more relevant to visitors.
keywords: cookies;privacy
seo-description: Target uses cookies to give website operators the ability to test which online content and offers are more relevant to visitors.
seo-title: Target Cookies
solution: Marketing Cloud,Analytics,Target,Social
title: Target Cookies
uuid: 44f7e32e-8d99-4682-8b54-8364d001b403
---

# Target Cookies{#target-cookies}

Target uses cookies to give website operators the ability to test which online content and offers are more relevant to visitors.

You can change these settings if needed, with the exception of the cookie duration. Consult your account representative when changing cookie settings.

>[!NOTE]
>
>Target users can also create customized third-party cookies.

<table id="table_54B402C6E19C4A70B1E27BC9DFF776EB"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Setting </th> 
   <th colname="col2" class="entry"> Information </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Cookie name </p> </td> 
   <td colname="col2"> <p>mbox. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Cookie domain </p> </td> 
   <td colname="col2"> <p>The second and top levels of the domains from which you serve the mbox. Because it is served from your company's domain, the cookie is a first party cookie. Example: <span class="filepath"> mycompany.com</span>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Server domain </p> </td> 
   <td colname="col2"> <p> <span class="filepath"> clientcode.tt.omtrdc.net</span>, using the client code for your Target account. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Cookie duration </p> </td> 
   <td colname="col2"> <p>The cookie remains on the visitor's browser two years from his or her last login. You cannot change the cookie duration. </p> </td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>If any of your domain names include a country code, such as [!DNL mycompany.co.uk], work with your Client Services to configure your [!DNL mbox.js] to support this.

The cookie keeps a number of values to manage how your visitors experience Target campaigns:

<table id="table_5245F72A2D5A4322B40ABB10B7DFB338"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Value </th> 
   <th colname="col2" class="entry"> Definition </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p> <span class="codeph"> session ID</span> </p> </td> 
   <td colname="col2"> <p>A unique ID for a user session. By default, this lasts 30 minutes. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> <span class="codeph"> pc ID</span> </p> </td> 
   <td colname="col2"> <p>A semi-permanent ID for a visitor's browser. Lasts until cookies are manually deleted. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> <span class="codeph"> check</span> </p> </td> 
   <td colname="col2"> <p>A simple test value used to determine if a visitor supports cookies. Set each time a visitor requests a page. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> <span class="codeph"> disable</span> </p> </td> 
   <td colname="col2"> <p>Set if visitor's load time exceeds the timeout configured in the <span class="filepath"> mbox.js</span> file. By default, this lasts 1 hour. </p> </td> 
  </tr> 
 </tbody> 
</table>

