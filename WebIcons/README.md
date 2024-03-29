
#   Icon Library   <img alt="HTML" src="https://camo.githubusercontent.com/7c61cf24e35e3840a10b91b8510a5b02eb188d5e0f255db135ca6dca9d7e26df/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f48544d4c2d4533344632363f6c6f676f3d68746d6c35266c6f676f436f6c6f723d7768697465267374796c653d666c6174" data-canonical-src="https://img.shields.io/badge/HTML-E34F26?logo=html5&amp;logoColor=white&amp;style=flat" style="max-width: 100%;"> <img alt="Css" src="https://camo.githubusercontent.com/ce6baf5ffef52faec6917ad2a2fa7e3c11252b891a16b419019b30b7ebfeefe0/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4353532d3135373242363f6c6f676f3d63737333266c6f676f436f6c6f723d7768697465267374796c653d666c6174" data-canonical-src="https://img.shields.io/badge/CSS-1572B6?logo=css3&amp;logoColor=white&amp;style=flat" style="max-width: 100%;"> <img alt="JavaScript" src="https://camo.githubusercontent.com/88bc7ef2e79a698a55b02b2bc222ea72279f587373920146759027cb72618189/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4a6176615363726970742d4637444631453f6c6f676f3d6a617661736372697074266c6f676f436f6c6f723d7768697465267374796c653d666c6174" data-canonical-src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&amp;logoColor=white&amp;style=flat" style="max-width: 100%;">

![image](https://user-images.githubusercontent.com/94997828/196003125-0532b802-012c-4135-8e8f-3af4e52d68d4.png)

#  Download Icon Library  💻 

Document : https://boxicons.com/

```bash
 npm install boxicons --save
```
   
# js body boxicons.js 

- Using the Web Component
Boxicons includes a Custom Element that makes using icons easy and efficient. To use it, add the boxicons.js file to the page:

```bash
<script src="https://unpkg.com/boxicons@2.1.4/dist/boxicons.js"></script>
```

# css head min.css

- Import the CSS
Copy-paste the stylesheet link into your head to load our CSS

```bash
<link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
```

# HTML
- To use an icon on your page, add a prefixbx- for regular icons, bxs- for solid icons & bxl- for logos followed by the icon name and seperate class with thebx:

```bash
<i class='bx bx-user'></i>
<i class='bx bxs-user'></i>
<i class='bx bxl-facebook-square'></i>
```

# Starter Templates 🛠

Create an HTML document and copy-paste the starter template

```bash
 <!doctype html>
 <html lang='en'>
   <head>
         <meta charset='utf-8'>
         <meta name='viewport' content='width=device-width, initial-scale=1, shrink-to-fit=no'>
         <!-- Boxicons CSS -->
         <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
         <title>Hello, Boxicons!</title>
   </head>
   <body>
          <h1>Hello, Boxicons!</h1>
          <i class='bx bx-hot'></i>
          <i class='bx bxs-hot'></i>
          <i class='bx bxl-facebook-square'></i>
   </body>
 </html>
```

A template for usage with the web component instead of icon font


```bash
     <!doctype html>
     <html lang='en'>
        <head>
             <meta charset='utf-8'>
             <meta name='viewport' content='width=device-width, initial-scale=1, shrink-to-fit=no'>
             <!-- Boxicons JS -->
             <link href='https://unpkg.com/boxicons@2.1.4/dist/boxicons.js' rel='stylesheet'>
             <title>Hello, Boxicons!</title>
        </head>
        <body>
            <h1>Hello, Boxicons!</h1>
            <box-icon name='hot'></box-icon>
            <box-icon type='solid' name='hot'></box-icon>
            <box-icon type='logo' name='facebook-square'></box-icon>
        </body>
     </html>
```

![image](https://user-images.githubusercontent.com/94997828/196004357-bd10eeee-2f0f-4a97-acc6-7a51e9f405e2.png)


----------------------------------------------------------
## Styling

![App Screenshot](https://user-images.githubusercontent.com/94997828/196004280-eb2d8df9-5b10-4bc0-a60d-a7f9b8a41234.png)

----------------------------------------------------

![image](https://user-images.githubusercontent.com/94997828/196004327-349a4603-c53a-4cbd-b787-82866a1c89e2.png)

