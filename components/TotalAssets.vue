<template>
  <div class="totalAsset">
    <div class="asset supplied">
      <div class="assetFigures">
        <div class="heading">
          Total Assets Supplied
        </div>
        <div class="assetFig">
          $1,201,052,129.03
          <span class="percent gain">+3.56</span>
        </div>
      </div>
      <div class="supplyButton">
        <img src="~/assets/supplied.png" alt="">
      </div>
    </div>

    <div class="asset borrowed">
      <div class="assetFigures">
        <div class="heading">
          Total Assets Borrowed
        </div>
        <div class="assetFig">
          $205,654,000.52
          <span class="percent lost">-13.56%</span>
        </div>
      </div>
      <div class="borrowButton">
        <img src="~/assets/borrowed.png" alt="">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TotalAssets'
}
</script>

<style>
.totalAsset{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 1.5rem;
    margin-bottom: 1.5rem;
}

.asset{
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: white;
    padding: 1.2rem;
    width: 49%;
    border-radius: 8px;
    box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.1), 0 2px 6px 0 rgba(0, 0, 0, 0.19);
}

.assetFigures{
  margin-right: 2rem;
}

.heading{
  color: gray;
  font-size: 0.8rem;
  font-weight: 600;
}

.assetFig{
  color: black;
  font-size: 1.5rem;
  font-weight: 700;
}

.percent{
  font-size: 0.8rem;
}

.gain{
  color: rgb(132, 219, 161);
}

.lost{
  color: red;
}
</style>
