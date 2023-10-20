<template>
<div class="container">
    <div class="navbar">
        <div class="nav-content">
            <div class="profile-picture">
                <img src="https://images.unsplash.com/photo-1554454188-f84071b1695f?crop=entropy&cs=srgb&fm=jpg&ixid=M3wzMjM4NDZ8MHwxfHJhbmRvbXx8fHx8fHx8fDE2OTUzOTY1MTV8&ixlib=rb-4.0.3&q=85" alt="">
            </div>
            <div class="nav-links">
                <div class="nav-link">
                    <div class="icon">
                        <svg viewBox="0 0 512 512" width="64" title="briefcase">
                            <path d="M320 336c0 8.84-7.16 16-16 16h-96c-8.84 0-16-7.16-16-16v-48H0v144c0 25.6 22.4 48 48 48h416c25.6 0 48-22.4 48-48V288H320v48zm144-208h-80V80c0-25.6-22.4-48-48-48H176c-25.6 0-48 22.4-48 48v48H48c-25.6 0-48 22.4-48 48v80h512v-80c0-25.6-22.4-48-48-48zm-144 0H192V96h128v32z" style='fill:#fff'/>
                        </svg>
                    </div>
                </div>
                <div class="nav-link">
                    <div class="icon">
                            <svg viewBox="0 0 512 512" width="64" title="table">
                                <path d="M464 32H48C21.49 32 0 53.49 0 80v352c0 26.51 21.49 48 48 48h416c26.51 0 48-21.49 48-48V80c0-26.51-21.49-48-48-48zM224 416H64v-96h160v96zm0-160H64v-96h160v96zm224 160H288v-96h160v96zm0-160H288v-96h160v96z" style='fill:#fff'/>
                            </svg>
                    </div>  
                </div>
                <div class="nav-link">
                    <div class="icon">
                        <svg viewBox="0 0 448 512" width="64" title="pen-square">
                            <path d="M400 480H48c-26.5 0-48-21.5-48-48V80c0-26.5 21.5-48 48-48h352c26.5 0 48 21.5 48 48v352c0 26.5-21.5 48-48 48zM238.1 177.9L102.4 313.6l-6.3 57.1c-.8 7.6 5.6 14.1 13.3 13.3l57.1-6.3L302.2 242c2.3-2.3 2.3-6.1 0-8.5L246.7 178c-2.5-2.4-6.3-2.4-8.6-.1zM345 165.1L314.9 135c-9.4-9.4-24.6-9.4-33.9 0l-23.1 23.1c-2.3 2.3-2.3 6.1 0 8.5l55.5 55.5c2.3 2.3 6.1 2.3 8.5 0L345 199c9.3-9.3 9.3-24.5 0-33.9z" style="fill:#fff"/>
                        </svg>
                    </div>
                </div>
                <div class="nav-link">
                    <div class="icon">
                        <svg viewBox="0 0 496 512" width="64" title="user-circle">
                            <path d="M248 8C111 8 0 119 0 256s111 248 248 248 248-111 248-248S385 8 248 8zm0 96c48.6 0 88 39.4 88 88s-39.4 88-88 88-88-39.4-88-88 39.4-88 88-88zm0 344c-58.7 0-111.3-26.6-146.5-68.2 18.8-35.4 55.6-59.8 98.5-59.8 2.4 0 4.8.4 7.1 1.1 13 4.2 26.6 6.9 40.9 6.9 14.3 0 28-2.7 40.9-6.9 2.3-.7 4.7-1.1 7.1-1.1 42.9 0 79.7 24.4 98.5 59.8C359.3 421.4 306.7 448 248 448z" style="fill:#fff"/>
                        </svg>
                    </div>
                </div>
                <div class="nav-link">
                    <div class="icon">
                        <svg viewBox="0 0 512 512" width="64" title="chart-bar">
                            <path d="M332.8 320h38.4c6.4 0 12.8-6.4 12.8-12.8V172.8c0-6.4-6.4-12.8-12.8-12.8h-38.4c-6.4 0-12.8 6.4-12.8 12.8v134.4c0 6.4 6.4 12.8 12.8 12.8zm96 0h38.4c6.4 0 12.8-6.4 12.8-12.8V76.8c0-6.4-6.4-12.8-12.8-12.8h-38.4c-6.4 0-12.8 6.4-12.8 12.8v230.4c0 6.4 6.4 12.8 12.8 12.8zm-288 0h38.4c6.4 0 12.8-6.4 12.8-12.8v-70.4c0-6.4-6.4-12.8-12.8-12.8h-38.4c-6.4 0-12.8 6.4-12.8 12.8v70.4c0 6.4 6.4 12.8 12.8 12.8zm96 0h38.4c6.4 0 12.8-6.4 12.8-12.8V108.8c0-6.4-6.4-12.8-12.8-12.8h-38.4c-6.4 0-12.8 6.4-12.8 12.8v198.4c0 6.4 6.4 12.8 12.8 12.8zM496 384H64V80c0-8.84-7.16-16-16-16H16C7.16 64 0 71.16 0 80v336c0 17.67 14.33 32 32 32h464c8.84 0 16-7.16 16-16v-32c0-8.84-7.16-16-16-16z" style="fill:#fff"/>
                        </svg>
                    </div>
                </div>
        </div>
        </div>  
    </div>
</div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.container{
    position: fixed;
}
.profile-picture{  
  overflow:hidden;
  >img{
    height:auto;
    width:100%;
    border-radius:50%;
    width:98px;
    height:98px;
    background-size:cover;
    object-fit:cover;
    }
}

.nav-content{
  display: flex;
  flex-direction:column;
  align-items: center;
  justify-content: space-evenly;
}

.nav-link{
  margin: 16px;
  cursor:pointer;
  display: flex;
}

.navbar{
  min-height:100vh;
  background:#FF6A6A;
  width:150px;
  display: flex;
  justify-content: center;
  &.profile-picture{
    width:100px;
    height:100px;
    color:white;
  }
}
</style>