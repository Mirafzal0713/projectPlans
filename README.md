# projectPlans
10:16 22.11.2021
Umumiy : 
Kerakli dasturlar o'rnatiladi  { 
Node.js , 
Git(https://git-scm.com/downloads), 
Visual Studio Code , 
}

birinchi kun
1 Kearki package lar o'rnaltiladi {
npx create-react-app <project name >  , 
va package.json dan portno 4000 ga ozgartirib qoyqamiz chunki backend 3000 port bogani uchun(set PORT=4000 && react-script start)
npm install react-bootstrap bootstrap@5.1.3 , 
va CDN link orqali chaqiramiz (
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"
  integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3"
  crossorigin="anonymous"
/>
),
npm install --save react-router-dom
google fonts dan kerakli font ni olamiz
va papkalar ichidagi fayllarni ichini tozzalab olamiz
2 project boshlanandi 
bunda biz project qanday bolishi va qanday papka va faylarni oz ichiga olish va nomlar ozaro bogliq boladi
   components
        header
          index.js navbardagi malumotlar header papka si orqali 
        Layout
          index.js ichida header boladi
        UI
          Input
            index.js kerak kod kamayishi uchun va inputlar ichidagi Label ,  Value , Placeholder, Onchange , Type kabi narsalar Input faylini ichidan props shaklida kelishi kerak

   containers  
     home 
       index.js shunda biz navabarni barcha sahifalarda Layout papkasi orqali chaira olamiz
     signup
       index.js shunda biz navabarni barcha sahifalarda Layout papkasi orqali chaira olamiz(
           bularni ichiga ham Form larni joylab olamiz
)
       
     signin
       index.js shunda biz navabarni barcha sahifalarda Layout papkasi orqali chaira olamiz (
           bularni ichiga ham Form larni joylab olamiz

)

   App.js da esa biz sahifani react-router dom dagi {BrowserRouter as Router, Route, Routes } qolab SPA yasab olamiz

 3. Malumotni oslish react-redux ni ishlatish
    npm install redux react-redux redux-thunk --save   
      redux-thunk(bu bizga dispatch va getState metodlarni ishatishga yordam beradi)


 4. Actions
      auth.action.js bu fayllar nima vazifa bacharishini yaozganimizdan keyin 
      constants.js   bu fayllar nima vazifa bacharishini yaozganimizdan keyin 
      index.js  orqali barcha faylda ishlashini belgilab qoyamiz (export * from './auth.actions';

    Store
      index.js ichida createStore() finction ishlatiladi
    Reducers
     index.js
     auth.reducers.js 
   App,js da esa Provider ishlatamiz
   
