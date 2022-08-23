<template>
  <div class="card">
    <img class="icon" src="../../assets/logo.png" alt="">
    <div class="cardBody">
      <div class="content">
        <div class="title">
          <div class="h5">小标题标题文字小标题标题文字小标题标题文字小标题标题文字小标题标题文字小标题标题文字小标题标题文字小标题标题文字小标题标题文字小标题标题文字小标题标题文字小标题标题文字</div>
          <div class="tag">tag</div>
        </div>
        <p>正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容正文内容</p>
      </div>
      <a href="#">查看更多 ></a>
    </div>
  </div>
</template>

<style>
.icon{
  width: 60px;
  height: 60px;
}
.card{
  padding:16px;
  background: linear-gradient(141.42deg, #F7F8FF -10.89%, #FFFFFF 75.81%);
  box-shadow: 0px 3px 6px -4px rgba(0, 61, 255, 0.1), 0px 0px 24px 8px rgba(0, 61, 255, 0.02);
  border-radius: 2px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap:16px;
}
.cardBody{
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  padding: 0px;
  gap: 24px;
}
.content{
  display: flex;
flex-direction: column;
align-items: flex-start;
gap: 16px;
}
.content .title{
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap:8px;
}
.h5{
font-weight: 500;
font-size: 16px;
line-height: 24px;
color: #333333;
/* max-width: 100%; */
overflow: hidden;
text-overflow: ellipsis;
text-align: left;
/* white-space: nowrap; */
-webkit-line-clamp: 2;
word-break: break-all;
-webkit-box-orient: vertical;
display: -webkit-box;
}
.tag{
  padding : 0px 8px;
  color:#999;
  font-size: 12px;
  line-height: 20px;
  text-align: center;
  border: 1px solid #D9D9D9;
  border-radius: 2px;
}
.content p{
  font-weight: 400;
  font-size: 14px;
  line-height: 22px;
  color: #999999;
/* max-width: 100%; */
overflow: hidden;
text-overflow: ellipsis;
text-align: left;
/* white-space: nowrap; */
-webkit-line-clamp: 6;
word-break: break-all;
-webkit-box-orient: vertical;
display: -webkit-box;
}
.cardBody a {
  font-weight: 400;
font-size: 14px;
line-height: 22px;
color: #4876FF;
}
 
</style>