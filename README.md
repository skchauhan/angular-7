Angular material
=============================


step1)
npm install -save @angular/material @angular/cdk
Component development kit(CDK)

step2)
@ngular/animations

step3)
import { BrowserAnimationsModule } from "@angular/platform-browser/animations"

step4) style.css
@import "~@angular/material/prebuilt-themes/indigo-pink.css";

step5)
npm install -save hammerjs
 import 'hammerjs'; ( in module app )

 step6)
&lt; link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet" &gt;

/////////////////


if angular version error

npm install --save-dev @angular/cli@latest


////////////

Add Bootstrap

 $ npm install --save bootstrap

 $ npm install --save jquery


In angular.js file 

     "styles": [
       "./node_modules/bootstrap/dist/css/bootstrap.css",
       "src/styles.css"              
     ],
     "scripts": [
       "./node_modules/jquery/dist/jquery.js",
       "./node_modules/bootstrap/dist/js/bootstrap.js"
     ]

