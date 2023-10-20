<template>
    <div class="main-content">
        <tab></tab>
        <div class="content-bar">
            <!--   Content Goes Here   -->
        </div>
        <div class="content-body">
            <div class="details-container">
                <div class="customer-details">
                    <div class="sales-id">Sales ID: 1234567</div>
                    <div class="client-name">Client: Mary Ann</div>
                    <div class="purchase-date">Purchase Date: 2/2/2023</div>
                    <div class="status">Status: In Transit <div class="circle"></div></div>
                    <button class="customer-info-button">Customer INFO</button>
                </div>
            </div>
            <div class="car-accordion-container">
                <div class="car-details">
                    <div class="car-image">
                        <div style="padding:150px;background:transparent; border: 1px solid black;">Sample Image</div>
                    </div>
                    <div class="car-details">
                        <div class="model">Model: ABC XYZ</div>
                        <div class="condition">Condition: New</div>
                        <div class="stock-number">Stock#: 1234567</div>
                        <div class="checklist-completed">Checklist Completed?
                            <input type="Checkbox" name="" id="">
                        </div>
                    </div>
                </div>
                <div class="accordion-container">
                    <accordion/>
                    <accordion/>
                    <accordion/>
                    <accordion/>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import Tab from './Tab.vue'
import Accordion from './Accordion.vue'
export default {
    components:{Tab,Accordion}
}
</script>

<style lang="scss" scoped>

/* FOR EXAMPLE IMAGE -- COMPONENTIZE IT LATER ON */
.details-container{
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    .customer-details{
        margin-bottom: 1rem;
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        .customer-info-button{
            padding: 10px 15px;
            background:transparent;
            border-radius: 20px;
            border: 1px solid black;
        }
    }
}
.car-accordion-container{
    display: flex;
    gap:1.5rem;
    .car-details{
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        .car-image{
            margin-bottom: 1rem;
        }
    }
}
/* ______________________________________________ */

.main-content{
  transform:translateY(20%);
  width: fit-content;
  max-width: 1600px;
  margin:auto 2rem;
  .content-bar{
    padding:16px; //replace with variable
    background: #FF6A6A; //replace with variable
    height:fit-content;
    border-radius: 10px 10px 0 0; //replace with variable
  }
  .content-body{
    padding:16px;//replace with variable
    background:#F6FAFF;//replace with variable
    border-radius: 0 0 10px 10px;//replace with variable
    box-shadow: 0 0 16px 0 #00000025;//replace with variable
  }
  .accordion-container{
    border-radius: .5rem;
    overflow: hidden;
  }
}
</style>