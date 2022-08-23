<template>
  <div class="titleGroup">
    <h1 class="title">标题文字</h1>
    <div class="subtitle">
      <p>正文内容</p>
      <a href="#">查看更多 ></a>
    </div>
  </div>
</template>

<style >
.title {
  font-weight: 500;
  font-size: 28px;
  line-height: 48px;
  color: black;
  text-align: center;
}
.subtitle {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  gap: 16px;
  font-size: 14px;
  line-height: 22px;
}
.subtitle p {
  color: #666;
}
.subtitle a {
  color: #4876FF;
}
.titleGroup {
  display: flex;
  flex-direction: column;
  gap: 16px;
}
@media (max-width: 770px) {
 .title {
  font-size: 16px;
  line-height: 24px;
}

.titleGroup {
  display: flex;
  flex-direction: column;
  gap: 8px;
  padding:16px 0px;
}
}
</style>