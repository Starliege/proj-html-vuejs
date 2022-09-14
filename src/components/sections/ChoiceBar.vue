<template>
    <div class="container">
        <ul>
            <li>Business</li>
            <li>Design</li>
            <li>Development</li>
            <li>Lifestyle</li>
            <li>Office Productivity</li>
        </ul>
    </div>
  </template>
  
  <script>
    export default {
      name: "ChoiceBar",
    };
    </script>
    
  
  <style lang="scss" scoped>
    .container {
        font-size: 14px;
        background-color: #292f47;
        height: 75px;
        display: flex;
        margin-bottom: 30px;
        
            ul {
                list-style-type: none;
                margin: auto ;
                
                li {
                    display: inline;
                    margin-right: 20px;
                    
                    img {
                        height: 17px;
                        align-self: center;
                        filter: grayscale(100%);
                    }
                }
            }
    }
  </style>