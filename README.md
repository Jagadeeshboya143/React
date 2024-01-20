 .parent{
    background-color: bisque;
 }
 .maindiv fdiv,img{
    height: 60px;
    width: 60px;
}
.maindiv{
    display: flex;
    justify-content: space-between;
    margin-left: 30px;
    margin-right    : 50px;
}
.head{
    margin-left: 400px;
    font-size: 40px;
}
.para{
    margin: 10px 100px;
}
.tag{
    
    margin: 10px 400px;
      
}
#t1{
  width: 30px;
  padding: 10px 10px;
  margin-right: 5px;
  background-color: rgb(216, 11, 11);
 
   font-weight: bold;
   border: none;
   box-shadow: 1px 2px 1px gray;
   font-size: 12px;
}
#t2{
    width: 80px;
    padding: 10px 10px;
    margin-right: 5px;
    font-weight: bold;
   border: none;
   box-shadow: 1px 2px 1px gray;
   font-size: 12px;
}
#t3{
    width: 50px;
    padding: 10px 10px;font-weight: bold;
    border: none;
    box-shadow: 1px 2px 1px gray;
    font-size: 12px;
  }
  .bom img{
 height: 300px;
 width: 400px;
 margin: 10px 300px;
  }

.second{
    
    background-color: rgb(127, 47, 47);
    height: 500px;
}
#h1{
   padding: 10px 400px;
}
#pa{
    margin: 10px 100px;
    color: white;
}
.main{
    display: flex;
    /* align-items: center; */
    justify-content: space-evenly;
}
.audi img{
    height: 90px ;
    width: 100px;
}
.video img{
    height: 90px;
    width: 100px;
}
#fir{
    margin-left: 40px;
}
#for{
    margin-left: 40px;
}
#b3{
   margin-left: 60px;
    padding: 10px 20px;
    background-color: rgb(224, 188, 176);
    color: white;
    box-shadow: 2px 3px 2px gainsboro;
    border: none;
}
#b4{
    margin-left: 60px;
     padding: 10px 20px;
     background-color: rgb(224, 188, 176);
     color: white;
     box-shadow: 2px 3px 2px gainsboro;
     border: none;
 }
 import "../Styles/Landing.css";
const Landing = () => {
  return (
    <div className="parent">
      <div className="maindiv">
          <div className="fdiv1">
          <img
            src="https://rochester.kidsoutandabout.com/sites/default/files/styles/970w/public/StorytimeClub_FinalLogo_CMYK_11.jpg?itok=h1FJV0PF"
            alt=""
          />
         </div>
         <div className="fdiv2">
          <img
            src="https://www.pngitem.com/pimgs/m/592-5927013_search-button-vector-facebook-icon-png-search-transparent.png"
            alt=""
          />
          <img
            src="http://www.pngmart.com/files/3/Sign-Up-Button-PNG-Transparent-Image.png"
            alt=""
          />
        </div>
      </div>
      <div className="head">Real Stories Real People</div>
      <div className="para">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione placeat
        libero animi fuga recusandae ex nam provident, autem iusto quo
        exercitationem odio nostrum fugit, aspernatur aliquid incidunt,
        quibusdam explicabo! Dignissimos.
      </div>
      <div className="tag">
        <input id="t1" type="text" placeholder="kids" />
        <input id="t2" type="text" placeholder="teenagers" />
        <input id="t3" type="text" placeholder="adults" />
      </div>
      <div className="bom">
        <img
          src="https://images.ctfassets.net/p0qf7j048i0q/6CoR3gS2NgLRPCV9qXURfQ/a380ddaba2b6f5d07799b4bd20f80bcb/G1147656393.jpg"
          alt=""
        />
        </div>
       <div className="second">
       <h1 id="h1">Choice is yours!</h1>
        <br /> 
        <p id="pa">Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus minus aut nisi architecto asperiores modi quia cumque quis necessitatibus blanditiis.
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur, eius!lorem5
        </p> <br /> <br /> <br />
       <div className="main">
       <div className="audi">
            <img id="fir" src="https://www.washingtonpost.com/rf/image_1484w/2010-2019/WashingtonPost/2016/06/10/Interactivity/Images/iStock_79272303_LARGE1465594741.jpg?t=20170517" alt="" />
            <img  id="sec"src="https://i.ytimg.com/vi/xqdMoStKYXc/maxresdefault.jpg" alt="" /> <br /> 
            <img src="https://i5.walmartimages.com/asr/a93da984-25c8-4f9d-a39f-bb566c9e76ec_1.52fc3ec8bcb5d26f905e94019cfbf497.jpeg" alt="" />
            <img src="https://i.pinimg.com/736x/0c/e6/45/0ce64583d47d992604f972d46055b8bd.jpg" alt="" />
            <img src="https://imgv2-1-f.scribdassets.com/img/word_document/296191451/original/9fffbc74a9/1631334504?v=1" alt="" /> <br /> <br />
           <button id="b3">View More</button>
            </div>
            <div className="video">
                <img id="for" src="https://1.bp.blogspot.com/-pf4NzKBEkvE/X1kdQlNEPVI/AAAAAAAAALI/AjOP0oJu91kFib7lar-t-FiDBCf8EvOYgCNcBGAsYHQ/s1600/20200909_202107_0000.png" alt="" />
                <img src="https://i.ytimg.com/vi/RVbMUq89_Kk/maxresdefault.jpg" alt="" /> <br />
                <img src="https://cdn2.penguin.com.au/covers/original/9780857989680.jpg" alt="" />
                <img src="https://www.srpublications.in/images/products/imga73.jpg" alt="" />
                <img src="https://crystalkeeper.files.wordpress.com/2021/01/short-stories-by-children-for-children-cover.jpg" alt="" />  <br /> <br />
                <button id="b4"> View More</button>
                 </div>
       </div>
       </div>
      </div>
    
  );
};

export default Landing;

