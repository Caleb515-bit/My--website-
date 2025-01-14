<!DOCTYPE html>
<html>
    <head>
        <meta http-equiv="content-type" content="application/xhtml+xml; charset=utf-8" />
        <title>Landing page</title>
        <link rel="stylesheet" href="index.css">
<style>*{
    padding: 0px;
    margin: 0px;
    background-color:#150036;
    color: white;
}
.container{
    color: white;
    font-family: Arial;
  }
  a{
     text-decoration:none;
     color: white;
  }
  a:hover{
      cursor:pointer;
      color:purple;
  }
  .formContainer{
      margin-top: 55px;
  }
  .headerContainer{
      display: grid;
      grid-template-columns:4fr 2fr 2fr 2fr;
  }
  .formTexth1{
      font-size:40px;
  }
  .formTextpara{
      font-size: 14px;
      line-height: none;
  }
  .formHeader{
    margin-bottom: 20px;
    line-height:35px;
    display:grid;
    grid-template-columns:2fr 100px;
  }
  .firstSecName{
      display:grid;
     grid-template-columns:1fr 1fr;
  }
 input,.companyName{
     border: 0px;
     padding: 10px;
     margin: 5px;
     width:100%;
     outline: none;
     background-color: white;
     color: #5C5C5C;
 }
 select{
     color: #8B8B8B;
 }
 .detailContainer{
     width: 350px;
     display: grid;
     grid-template-rows:1fr 1fr 1fr 1fr 1fr 1fr;
 }
 .lastNameForm{
  margin-left: 10px;   
 }
 .checkText{
     display: flex;
     flex-direction: columns;
     margin-top:20px;
     margin-bottom:20px;
     width: 350px;
 }
 .check{
   border: none;
 }
 .text{
     font-size:15px;
     line-height:15px;
 }
 .button{
     width:350px;
     padding-top:5px;
     padding-bottom: 5px;
     color: white;
     font-weight: bold;
     font-size:17px;
     border: none;
     background-color:#8D33FF;
     transition: background-color 0.2s,color 0.2s;
 }
 .button:hover{
     border:1px solid puple;
     background-color:white;
     color: purple;
 }
.formContainer{
    margin-left:5px;
}
.product,.resource,.prizing{
 border-style: none;  
margin: none;
outline: none;
color: white;
}
.image{
 width: 100px;
 height: 100px;
 margin: none;
 border-radius:10px;
}
</style>
    </head>
    <body>
        <div class="container">
            <div class="headerContainer">
             <div class="">
               <p style="font-weight:bold;">Compaign Monitor</p> 
               </div>
              <div class="">
             <select name="product" class="product">
                 <option value="Product">Product</option>
             </select>
             </div>
             <div class="">
                 <select name="" class="prizing">
                     <option value="">Prizing</option>
                 </select>
                </div>
             <div class="">
                 <select name="" class="resource">
                 <option value="">Resource</option>                    
                 </select>
             </div> 
            </div>
              </div>
         <!--form-->
         <div class="formContainer">
            <div class="formHeader">
                <div>
             <h1 class="formTexth1">Request a live demo.</h1> 
              <p class="formTextpara">Fill out your detail to get a live demo on Compaign Monitor </p>         </div>       
             <div>
              <img class="image" src="CompaignImage.jpg"/>      </div>
              </div>
             <div class="detailContainer">
                 <div class="firstSecName">
              <div class="">
               <input type="text" placeholder="First Name"/>   
              </div>   
              <div class="lastNameForm">
                  <input type="text" placeholder="Last Name"/>
              </div>                     
                 </div>
              <div>
                  <input type="text" placeholder="Company Email"/>
              </div>
              <div>
                  <input type="text" placeholder="Company Name"/>
              </div>
              <div>
                  <input type="text" placeholder="Phone Number"/>
              </div>
              <div>
                  <input type="text" placeholder="Job type"/>
              </div>
              <div>
                 <select name="companyName" id="companyName" class="companyName">
                     <option>company Name</option>
                 </select>
              </div>
              </div>
              <!--after detail-->
              <div class="">
                  <div class="checkText">
                  <div class="check">
                  <input type="checkbox"/>    
                  </div>
                  <div class="text">
                  <p>Rom.8.13 - For if ye live after the flesh, ye shall die: but if ye through the Spirit do mortify the deeds of the body, ye shall live.
</p>    
                  </div>                      
                  </div>
                 <div class="button" style="margin-bottom:40px;">
                     <button class="button" type="submit" >Submit</button>
                 </div>
              </div>
             </div>
    </body>
</html>
