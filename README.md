v# project
* {
  box-sizing: border-box;
}

body{
	margin: 0;
	padding: 0;
  font-family: "Comic Sans MS", cursive, sans-serif;
}

.row{
  margin-top: 5%;
  margin-bottom: 5%;
}

h1 {
  margin-bottom: 15px;
  text-align: center;
  color: #ff4532;
  font-size: 50px;
}


.box{
  width: 100%;
  overflow: none;
}


.content-name{
  overflow: none;
  text-align: center;
  border: 4px solid black;
  width: 100px;
  height: 40px;
  padding: 5px;
  float: right;
  margin-right: 36px;
  margin-top: 0px;
  font-weight: bold;
  position: relative;
}

.content{
  border: 5px solid black;
  width: 90%;
  height: auto;
  margin: 2.5%;
  color: black
  font-size: 25px;
  padding: 2%;
  padding-top: 55px;
  background-color: rgba(0,0,0,0.3);
}

.name1{
  background-color: #FFB6C1;
}

.name2{
  color: white;
  background-color: #FF0000;
}
.name3{
  background-color: #FFFF00;
}


/********** Large devices only **********/
@media (min-width: 992px) {
  .col-lg-4 {
  	float: left;
    width: 33.33%;
  }
}
/********** Medium devices only **********/
@media (min-width: 768px) and (max-width: 991px) {
  .col-md-6,.col-md-12 {
    float: left;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-12 {
    margin-left: -10px;
    width: 100%;
  }
  .name3{
    margin-right: 65px;
    width: 100px;
  }
}

@media (min-width: 0px) and (max-width: 767px) {
  .col-sm-12 {
  	float: left;
    width: 100%;
  }
  .content-name{
    margin-right: 30px;
  }
}
