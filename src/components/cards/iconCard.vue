<template>
  <div class="card">
    <div class="icon64"></div>
    <div class="cardBody">
      <div class="content">
        <div class="title">
          <h5>小标题标题文字</h5>
          <div class="tag">tag</div>
        </div>
        <p>正文内容</p>
      </div>
      <a href="#">查看更多 ></a>
    </div>
  </div>
</template>

<style>
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
h5{
font-weight: 500;
font-size: 16px;
line-height: 24px;
color: #333333;
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
}
.cardBody a {
  font-weight: 400;
font-size: 14px;
line-height: 22px;
/* identical to box height, or 157% */



/* primary/1 常规 */

color: #4876FF;
}
 
</style>