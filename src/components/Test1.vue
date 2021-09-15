<template>
<body>

  <div class="floating-icon">
     <i class="fas fa-envelope chat-open"></i>

  </div>

    <nav class="top-nav">
        <div class="hamburger-menu"> 
        <div class="wrapper-menu">
            <div class="line-menu half start"></div>
            <div class="line-menu"></div>
            <div class="line-menu half end"></div>
        </div>
        </div>

        <div class="play-wrapper">
        <router-link href="www.beta.Playtonia.com">
          <div class="playtonia-logo">
              <img src="@/assets/img/logo1.png">
                  <!-- <img src="@/assets/img/Playtonia White.png"> -->
          </div>
        </router-link>
        <div class="game-select">
            <i class="fas fa-dice"></i><span>Games</span>
        </div>
        </div>

        

        <div class="pro-noti">
          <div class="notification">
            <div class="notification-noti"><i class="fas fa-bell"></i></div>
            <div class="notification-chat"><i class="fas fa-envelope chat-open"></i></div>
          </div>
          <div class="profile_card">
              <div class="profile_card_fig">
                  <img src="@/assets/img/profile.jpg">
                  <div class="participants_card_fig_teamlogo">
                      <img src="icons/shield3.png">
                  </div>
              </div>
              <div class="profile_card_conent">
                  <div class="participants_card_title">varun kishore</div>
                  <div class="participants_card_discription">
                    <span class="participants_card_discription_span"><img src="@/assets/img/leaf_stat.png"> 20000</span>
                    <span class="participants_card_discription_span"><img src="@/assets/img/coin_stat.png"> 20000</span>
                  </div>
              </div>
          </div>
        </div>

        

            <!-- <div class="user-info" >
                    <img src="./icons/notification.svg"/>
                <img src="./icons/chat.svg"/>
                <img class="user-img" src="https://lh3.googleusercontent.com/-dqYrsoGNPUc/AAAAAAAAAAI/AAAAAAAAAAA/ACHi3rfmJgTE30c8iD2c90i5SrByzjVjEw/mo/photo.jpg?sz=46"/>
            </div> -->

    </nav>
    <div class="sidebar">
        
       <div class="icons">
        <div class="play-btn i">
           <i class="fas fa-play"></i>
        </div>
        <router-link  to="/">
            <div class="wrapper">
              <i class="fas fa-gamepad"></i>
            </div>
            <!-- <div class="wrapper-name">dashboard</div> -->
        </router-link> 
        <router-link class="active" to="/">
            <div class="wrapper">
                <i class="fas fa-trophy"></i>
            </div>
            <!-- <div class="wrapper-name">event</div> -->
        </router-link> 
        <router-link to="/">
            <div class="wrapper">
                <i class="fas fa-door-open"></i>
            </div>
            <!-- <div class="wrapper-name">lobby</div> -->
        </router-link> 
        <router-link to="/">
            <div class="wrapper">
                <i class="fas fa-users"></i>
            </div>
            <!-- <div class="wrapper-name">team</div> -->
        </router-link>
        <router-link to="/">
            <div class="wrapper">
                <i class="fas fa-cart-arrow-down"></i>
            </div>
            <!-- <div class="wrapper-name">market</div> -->
        </router-link> 
        
        <router-link to="/">
            <div class="wrapper">
                <i class="fas fa-handshake"></i>
            </div>
            <!-- <div class="wrapper-name">friends</div> -->
        </router-link>
       </div>
    </div>
    <!--chat sidebar-->

<!-- notification_bar -->
  <div class="notification_bar">
    <div class="notification_bar-pointer"></div>
    <div class="notification_bar_content">
      <div class="notification_card">
        <div class="notification_card_fig">
          <img src=" https://picsum.photos/40/40" >
          <div class="notification_card_fig_logo">
              <img src="icons/shield1.png">
          </div>
        </div>
        <div class="notification_card_time">04:45 PM</div>
        <div class="notification_card_conent">
           <div class="notification_card_title">
            <router-link href="">ramesh kumar</router-link> added you as friend .
          </div>
        </div>
        <div class="notification_card_request">
          <span>
            <router-link to="/" class=" ">accept</router-link>
            <router-link to="/" class=" ">remove</router-link> 
          </span>
         </div>

      </div>
      <div class="notification_card">
        <div class="notification_card_fig">
          <img src=" https://picsum.photos/40/40" >
          <div class="notification_card_fig_logo">
              <img src="icons/shield1.png">
          </div>
        </div>
        <div class="notification_card_time">04:45 PM</div>
        <div class="notification_card_conent">
           <div class="notification_card_title">Thankyou for joining tournament  <router-link href="">son of gun</router-link> .</div>
        </div>
      </div>
      <div class="notification_card">
        <div class="notification_card_fig">
          <img src=" https://picsum.photos/40/40" >
          <div class="notification_card_fig_logo">
              <img src="icons/shield1.png">
          </div>
        </div>
        <div class="notification_card_time">04:45 PM</div>
        <div class="notification_card_conent">
           <div class="notification_card_title">You left the tournament  <router-link href="">son of gun</router-link> .</div>
        </div>
      </div>
      <div class="notification_card">
        <div class="notification_card_fig">
          <img src=" https://picsum.photos/40/40" >
          <div class="notification_card_fig_logo">
              <img src="icons/shield1.png">
          </div>
        </div>
        <div class="notification_card_time">04:45 PM</div>
        <div class="notification_card_conent">
           <div class="notification_card_title">Your team <router-link href="">danger-x</router-link> left the tournament  <router-link href="">son of gun</router-link> .</div>
        </div>
      </div>
      <div class="notification_card">
        <div class="notification_card_fig">
          <img src=" https://picsum.photos/40/40" >
          <div class="notification_card_fig_logo">
              <img src="icons/shield1.png">
          </div>
        </div>
        <div class="notification_card_time">04:45 PM</div>
        <div class="notification_card_conent">
           <div class="notification_card_title"> <router-link href="">ramesh kumar</router-link> invited you to join his team <router-link href="">danger-x</router-link> .
           </div>
        </div>
        <div class="notification_card_request">
          <span>
            <router-link to="/" class=" ">accept</router-link>
            <router-link to="/" class=" ">remove</router-link> 
          </span>
         </div>

      </div>
      <div class="notification_card">
        <div class="notification_card_fig">
          <img src=" https://picsum.photos/40/40" >
          <div class="notification_card_fig_logo">
              <img src="icons/shield1.png">
          </div>
        </div>
        <div class="notification_card_time">04:45 PM</div>
        <div class="notification_card_conent">
           <div class="notification_card_title"> <router-link href="">ramesh kumar</router-link> agree the invite to join your team <router-link href="">danger-x</router-link> .</div>
        </div>
      </div>
      <div class="notification_card">
        <div class="notification_card_fig">
          <img src=" https://picsum.photos/40/40" >
          <div class="notification_card_fig_logo">
              <img src="icons/shield1.png">
          </div>
        </div>
        <div class="notification_card_time">04:45 PM</div>
        <div class="notification_card_conent">
           <div class="notification_card_title"><router-link href="">ramesh kumar</router-link> added you as friend .</div>
        </div>
      </div>
      <div class="notification_card">
        <div class="notification_card_fig">
          <img src=" https://picsum.photos/40/40" >
          <div class="notification_card_fig_logo">
              <img src="icons/shield1.png">
          </div>
        </div>
        <div class="notification_card_time">04:45 PM</div>
        <div class="notification_card_conent">
           <div class="notification_card_title">You left the tournament  <router-link href="">son of gun</router-link> .</div>
        </div>
      </div>
      <div class="notification_card">
        <div class="notification_card_fig">
          <img src=" https://picsum.photos/40/40" >
          <div class="notification_card_fig_logo">
              <img src="icons/shield1.png">
          </div>
        </div>
        <div class="notification_card_time">04:45 PM</div>
        <div class="notification_card_conent">
           <div class="notification_card_title"> <router-link href="">ramesh kumar</router-link> added you as friend</div>
        </div>
      </div>
      <div class="notification_card">
        <div class="notification_card_fig">
          <img src=" https://picsum.photos/40/40" >
          <div class="notification_card_fig_logo">
              <img src="icons/shield1.png">
          </div>
        </div>
        <div class="notification_card_time">04:45 PM</div>
        <div class="notification_card_conent">
           <div class="notification_card_title"> <router-link href="">ramesh kumar</router-link> added you as friend</div>
        </div>
      </div>
    </div>
  </div>
<!-- notification bar end -->



    <div class="chat-sidebar">
        <div class="team-box">
            <div class="team-box-header"> my team <span>6</span></div>
            <div class="team-box-content">
                <div class="team-box-content-inner hidescroll">

                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="gamelogo/CSGO-TEAM-THUMB.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">varun kishore</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>

                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40" >
                        <div class="participants_card_fig_teamlogo">
                            <img src="gamelogo/LOL-TEAM-THUMB.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">ramesh kumar</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>

                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="gamelogo/pubgmobile-TEAM-THUMB.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="gamelogo/pubgmobile-TEAM-THUMB.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                </div>
                <div class="manage-team">
                    <i class="fas fa-cogs"></i><span>manage teams</span>
                </div>
            </div>
        </div>
        <div class="chat-box">
            <div class="team-box-header"> my friends <span>8</span></div>
            <div class="team-box-content">
                <div class="chat-box-content-inner">
                    <div class="field-input">
                        <input type="text" placeholder="Find Friends..."/><span><i class="fas fa-user-plus"></i> </span>
                    </div>

                    <div class="participants_card-outer hidescroll">
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40" >
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40" >
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield2.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>

                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                    <div class="participants_card">
                      <div class="participants_card_fig">
                        <img src=" https://picsum.photos/40/40">
                        <div class="participants_card_fig_teamlogo">
                            <img src="icons/shield1.png">
                        </div>
                      </div>
                      <div class="participants_card_flag"><i class="far fa-comments"></i></div>
                      <div class="participants_card_conent">
                         <div class="participants_card_title">Tony Stark Tony Stark Tony Stark Tony Stark</div>
                         <div class="participants_card_discription">Join me to Huntresst them all!</div>
                      </div>
                    </div>
                </div>



                </div>
            </div>
        </div>
    </div>
    <!--chat sidebar-->
    <main class="main-layout__content">

      <router-link href="#createserver_popup">
        <div style="color: white"><i class="fas fa-pencil-alt"></i><span>Daily rewards</span></div>
      </router-link> 
      
    </main> 

    <div id="createserver_popup" class="overlay">

      <div class="popup">
        <router-link class="close" to="/"><i class="far fa-times-circle"></i></router-link>
        <div class="popup_header">
          <h4>Daily rewards</h4>         
        </div>
        <!-- for general id -->
        <div class="popup_content">
          <div id="black-grd"></div>
          <div class="reward_wrapper">
            <div class="rewardcard a">
              <div class="daycard_header">day 1</div>
              <div class="daily_image" >
                  <img src="@/assets/img/3.png">
                </div>
              <div class="daily_image_name"> battel points</div>
            </div>
            <div class="rewardcard b">
              <div class="daycard_header">day 2</div>
              <div class="daily_image">
                <img src="@/assets/img/3.png">
              </div>
              <div class="daily_image_name"> battel points</div>
            </div>
            <div class="rewardcard c">
              <div class="daycard_header">day 3</div>
              <div class="daily_image">
                <img src="@/assets/img/3.png">
              </div>
              <div class="daily_image_name"> battel points</div>
            </div>
            <div class="rewardcard d">
              <div class="daycard_header">day 4</div>
              <div class="daily_image">
                <img src="@/assets/img/3.png">
              </div>
              <div class="daily_image_name"> battel points</div>
            </div>
            <div class="rewardcard e">
              <div class="daycard_header">day 5</div>
              <div class="daily_image">
                <img src="@/assets/img/3.png">
              </div>
              <div class="daily_image_name"> battel points</div>
            </div>
            <div class="rewardcard f">
              <div class="daycard_header">day 6</div>
              <div class="daily_image">
                <img src="@/assets/img/3.png">
              </div>
              <div class="daily_image_name"> battel points</div>
            </div>
            <div class="rewardcard g">
              <div class="daycard_header">day 7</div>
              <div class="daily_image">
                <img src="@/assets/img/3.png">
              </div>
              <div class="daily_image_name"> battel points</div>
            </div> 
          </div>
        </div>
        <!-- for ganeral id end-->

      </div>
    </div>



</body>





</template>

<script>
var wrapperMenu = document.querySelector('.wrapper-menu');

wrapperMenu.addEventListener('click', function(){
    wrapperMenu.classList.toggle('open');  

})



$(".notification-chat").click(function(){
    $('.chat-sidebar').toggle();
});

$(".notification-noti").click(function(){
    $('.notification_bar').toggle();

});



$(".floating-icon").click(function(){
    $('.chat-sidebar').toggle();
    $('.chat-open').toggleClass('fa-times')

});


$(".hamburger-menu").click(function(){
    $('.sidebar').toggle();

});




</script>

<style scoped>
.hidescroll::-webkit-scrollbar {
    width: 5px; 
    height: 5px; /* remove scrollbar space */
    background: #ffffff00; 
    border-radius: 4px;
     /* optional: just make scrollbar invisible */
}
/* optional: show position indicator in red */
.hidescroll::-webkit-scrollbar-thumb {
    background: #ffffff1a;
    border-radius: 4px;
}
/*.hidescroll::-webkit-scrollbar-track {
  border-radius: 4px;
}*/


.sidebar{
    position: fixed;
    left: 0;
    top: 0;
    height: 100vh;
    width: 70px;
    background: #1b2731;
    box-shadow: 5px 7px 6px rgba(0, 0, 0, 0.25);  
    display: block; 
    z-index: 2;
}
.top-nav{
    display: flex;
    justify-content: space-between;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 60px;
    background: inherit;
    box-shadow: 3px 2px 20px 3px rgba(0,0,0,.16);
    z-index: 3;
}
.hide{
    display: none !important;
}
.play-wrapper{
    margin-left: 10px;
    display: flex;
    float: left;
}
.playtonia-logo{
  position: relative;
  /*width: 160px;
  height: 100%;*/
    width: 50px;
    height: 60px;
    display: flex;


}


.playtonia-logo img{
  width: 100%;
  margin: auto 0;
}

.game-select{
    width: auto;
    margin-left: 10px;
    min-width: 110px;
    padding:21px 8px;
    text-transform: uppercase;
    -webkit-box-direction: normal;
    -ms-flex-direction: row;
    flex-direction: row;
    font-size: 16px;
    color: #6c829d;
    background-color: transparent;
    border: none;
    letter-spacing: .3px;
    outline: none;
    text-align: center;
    cursor:pointer;
    font-weight: 700;
    /*margin:auto 0;*/
    /*align-self: center;*/

}
.game-select i{
  font-size: 14px;
  margin: 0 10px 0 0;
}
.game-select:hover{
  background-color: #6c829d0d;
  color: #becde3;
}
.game-select:hover i{
  color: #3CA3F0;
}


/* hamburger css */
.hamburger-menu {
  background: #1b2731;
  display: none;
}
.wrapper-menu {
    width: 20px;
    height: 20px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    cursor: pointer;
    transition: transform 330ms ease-out;
    /*margin: 21px;*/
    float: left;
    /*padding: 20px 22px;*/
  }
  
  .wrapper-menu.open {
    transform: rotate(-45deg);  
  }
  
  .line-menu {
    /*background-color: #e3e4e6;*/
    background-image: linear-gradient(to right, rgb(79, 172, 254) 0%, rgb(0, 242, 254) 100%);
    border-radius: 5px;
    width: 100%;
    height: 3px;
  }
  
  .line-menu.half {
    width: 50%;
  }
  
  .line-menu.start {
    transition: transform 330ms cubic-bezier(0.54, -0.81, 0.57, 0.57);
    transform-origin: right;
  }
  
  .open .line-menu.start {
    transform: rotate(-90deg) translateX(3px);
  }
  
  .line-menu.end {
    align-self: flex-end;
    transition: transform 330ms cubic-bezier(0.54, -0.81, 0.57, 0.57);
    transform-origin: left;
  }
  
  .open .line-menu.end {
    transform: rotate(-90deg) translateX(-3px);
  }
  
/* end of hamburger css */

/* nav user profile  */
.profile_card{

  flex-direction: row;
    -ms-flex-align: stretch;
    align-items: stretch;
    /*min-height: 86px;*/
    position: relative;
    z-index: 1;
    display: flex;
    border-radius: 4px;
    float: right;
    height: 100%;
    width: 280px;
}
.profile_card:hover {
    background-color: #6c829d0d;
}
.profile_card:before {
    content: "";
    position: absolute;
    top: 10px;
    width: 1px;
    background-color: #2a2d30;
    /* background-color: #101820; */
    -webkit-box-shadow: 1px 0 0 #000000;
    box-shadow: 1px 0 0 #000000;
    height: calc(100% - 20px);
    left: -10px;
}

.profile_card_fig{
    flex-basis: 40px;
    -ms-flex-item-align: center;
    align-self: center;
    position: relative;
}
.profile_card_fig img{
  display: block;
  border-radius: 5px;
}
.profile_card_conent {
    flex: 1;
    display: -ms-flexbox;
    display: flex;
    -ms-flex-direction: column;
    flex-direction: column;
    -ms-flex-pack: center;
    justify-content: center;
    padding: 0px 15px;
}
.profile_card > .profile_card_conent > .participants_card_title{
  max-width: 200px!important;
  font-size: 15px;
    margin-bottom: .2em;
}
.profile_card > .profile_card_conent > .participants_card_discription{
  max-width: 200px!important;
   margin: 0px;
}

.participants_card_discription_span{
  margin-right: 20px;
}
.participants_card_discription_span img{
  width: 15px;
  margin-right: 5px;
  margin-bottom: -3px;
}

.pro-noti{
  float: right;
  display: flex;
  flex-direction: row;
  height: 100%;
}
.notification{
  margin-right: 20px;
  display: flex;
}
.notification > .notification-noti , .notification-chat {
  margin: auto 20px;
  font-size: 20px;
  color: #6c829d;
  transition: all .2s ease-in-out;
}
.notification-noti:hover , .notification-chat:hover{
  color: white;
  transform: scale(1.1);

}


/* sidebar icons  */
.sidebar .icons{
    margin-top: 75px;
}
.play-btn{
    padding: 13px;
    display: block;
    text-align: center;
    

}
.play-btn img{
  width: 43px;
}

.sidebar a {
    display: flex;
    text-align: center;
    justify-content: center;
    padding: 13px;
    transition: all 0.3s ease;
    color: white;
  }
  
  
  .icons > .active::before{
    content: "";
    position: absolute;
    width: 5px;
    background-color: #3CA3F0;
    -webkit-box-shadow: 1px 0 0 #303e53;
    box-shadow: 1px 0 0 #303e53;
    height: 40px;
    left: 0;
    -webkit-clip-path: polygon(0% 0%, 40% 0, 100% 50%, 40% 100%, 0% 100%);
    clip-path: polygon(0% 0%, 40% 0, 100% 50%, 40% 100%, 0% 100%);
  }
  .icons .active .wrapper{
    /*background:  #3CA3F0;*/
    background-image: linear-gradient(to right, rgb(79, 172, 254) 0%, rgb(0, 242, 254) 100%);
    border-radius: 8px;
    padding: 7px;
    font-size: 22px;
    box-shadow: 3px 2px 20px 3px rgba(0,0,0,.16);
  }
  .icons a .wrapper{
    
    /*border-radius:8px;*/
    padding: 7px;
    font-size: 22px;
   
  }

  .icons a .wrapper:hover{
    /*background:  #3CA3F0;*/
    /*border-top-left-radius:8px;
    border-bottom-left-radius:8px;
    */
    background-image: linear-gradient(to right, rgb(79, 172, 254) 0%, rgb(0, 242, 254) 100%);
    border-radius: 8px;
    padding: 7px;
    
    box-shadow: 3px 2px 20px 3px rgba(0,0,0,.16);

  }
  /* extention text
  .wrapper-name{
    display: none;
    justify-content: center;
    align-self: center;
    padding: 7px;
    text-decoration-line: unset;
    text-transform: capitalize;
    font-size: 18px;
    text-decoration: none!important;
    transition: all 5.9s ease;
    

}
  .icons a .wrapper:hover + .wrapper-name {
     display : block;
     transition: all 5.9s ease;
     background-image: linear-gradient(to right, rgb(79, 172, 254) 0%, rgb(0, 242, 254) 100%);
  }*/
  

/* sidebar icons*/


 /*notification_bar-start*/

 .notification_bar{

    display: none;
    position: fixed;
    right:291px;
    top: 60px;
    background: #1b2731;
    width: 500px;
    box-shadow: 2px 3px 6px rgba(0,0,0,.5);
    z-index: 3;
 }
 
 .notification_bar-pointer{ 
    position: absolute;
    width: 0px;
    height: 0px;
    border: 11px solid transparent;
    border-bottom: 11px solid #1b2731;
    top: -22px;
    right: 87px;
 }

 /* .notification_bar_content{
 
 } */

 .notification_card{
    flex-direction: row;
    -ms-flex-align: stretch;
    align-items: stretch;
    /* min-height: 86px; */
    position: relative;
    z-index: 1;
    display: flex;
    padding: 6px 15px;
    border-bottom: 1px solid #ffffff1a;
    overflow: hidden;

 }
 .notification_card:hover {
    background-color: #6c829d0d;
}

.notification_card_time {
    position: absolute;
    z-index: 1;
    font-size: 12px;
    color: #ffffff3b;
    bottom: 2px;
    right: 10px;
}
.notification_card_fig{
    flex-basis: 40px;
    -ms-flex-item-align: center;
    align-self: center;
    position: relative;
}
.notification_card_fig img {
    border-radius: 5px;
}
.notification_card_fig_logo{
    position: absolute;
    z-index: 1;
    font-size: 12px;
    color: #ffffff3b;
    bottom: 3px;
    right: 10px;
}
.notification_card_fig_logo {
    position: absolute;
    right: -6px;
    bottom: -6px;
    width: 20px;
}
.notification_card_conent{
    flex: 1;
    display: -ms-flexbox;
    display: flex;
    -ms-flex-direction: column;
    flex-direction: column;
    -ms-flex-pack: center;
    justify-content: center;
    padding: 0px 15px;
}
.notification_card_title{
  font-size: 13px;
     margin-bottom: .2em; 

     line-height: 1.3; 
    /* letter-spacing: -.02em; */
    font-weight: 500;
    text-align: left;
    /* text-overflow: ellipsis; */
    overflow: hidden;
    /* white-space: nowrap; */
    /* max-width: 130px; */
    color: #ffffff90;
}
.notification_card_title a{
  font-size: 14px;
  color: #fff;
  font-weight: 600;
}
 
 .notification_card_request{
  text-align: center;
  display: flex;
  align-self: center;
 }
.notification_card_request span a {
    text-shadow: 1px 1px #1a8074;
    padding: 4px 6px;
    font-size: 10px;
    line-height: 2.5em;
    border-radius: 4px;
    transition: all .2s ease-in-out;
    color: #fff;
    text-transform: uppercase;
    margin-right: 10px;
    background-image: linear-gradient(to right, rgb(79, 172, 254) 0%, rgb(0, 242, 254) 100%);
} 
.notification_card_request span a:hover { 
      box-shadow: 0px 1px 20px 0px #3CA3F0;
      transform: scale(1.1);      
}

 /*notification_bar-end */


/* chat sidebar */

.chat-sidebar{
    display: none;
    position: fixed;
    right: 0;
    top: 60px;
    background: #1b2731;
    width: 290px;
    height: 100%;
    box-shadow: -2px -3px 6px rgba(0, 0, 0, 0.20);
    z-index: 2;
}
.team-box{
  margin-top: 15px;
}
.team-box-header{
  background-color: #0d16209e;
    color: #becde3;
    padding: 10px 15px;
    text-transform: uppercase;
    font-weight: 700;
    display: flex;
}
.team-box-header span{
    margin-left: 15px;
    background-color: #ffffff1a;
    padding: 4px 5px;
    border-radius: 5px;
    font-size: 12px;
    text-align: center;
}
.team-box-content{
  padding: 15px 20px;
}
.team-box-content-inner{
  border-bottom: 2px solid #ffffff1a; 
  height: 174px;
  overflow: auto;

}
.participants_card{
    flex-direction: row;
    -ms-flex-align: stretch;
    align-items: stretch;
    /*min-height: 86px;*/
    position: relative;
    z-index: 1;
    display: flex;
    border-radius: 4px;
    
    margin-bottom: 15px;
}

.participants_card_fig{
    flex-basis: 40px;
    -ms-flex-item-align: center;
    align-self: center;
    position: relative;
}
.participants_card_fig img{ 
  border-radius: 5px;
}
.participants_card_fig_teamlogo {
    position: absolute;
    right: -6px;
    bottom: -6px;
    width: 20px;
}
.participants_card_fig_teamlogo img{
  border-radius: 50%;
}

.participants_card_conent{
      flex: 1;
    display: -ms-flexbox;
    display: flex;
    -ms-flex-direction: column;
    flex-direction: column;
    -ms-flex-pack: center;
    justify-content: center;
    padding: 0px 15px;
}
.participants_card_title , .participants_card_discription {
    font-size: 14px;
    margin-bottom: .4em;
    text-transform: capitalize;
    line-height: 1.2;
   /* letter-spacing: -.02em;*/
    font-weight: 700;
    text-align: left;
    text-overflow: ellipsis;
    overflow: hidden;
    white-space: nowrap;
    max-width: 130px;
    
    color: #fff;

}
.participants_card_discription{
  font-size: 12px;
  color: #ffffff3b;
  max-width: 150px;
}
.participants_card_flag{
  position: absolute;
    z-index: 12;
    font-size: 18px;
    color:#ffffff3b;
    right: 5px;
    top: 10px;
}
.participants_card:hover{
  background-color: #6c829d0d;
}
.participants_card:hover .participants_card_flag{
  transform: scale(1.1);
  color: white;
}
/*.participants_card_flag:hover{
  transform: scale(1.1);
  color: white;
}*/

.manage-team{
 text-align: right;
 font-size: 12px;
 color: #ffffff3b;
 padding: 10px;
 text-transform: capitalize;

}
.manage-team i{
  font-size: 10px;
  margin: 0 10px 0 0;
}
.manage-team:hover{
  color:#6c829d;
}

/* .chat-box-content-inner{
  /*border-bottom: 2px solid #ffffff1a;*/
/* } */ 
.participants_card-outer{
  padding-top: 16px;
  /*height: 100vh;*/
  height: calc(100vh - 465px);
  overflow: auto;
}

.field-input {
  text-align: center;
  border-bottom: 2px solid #ffffff1a;
  display: flex;
  
}
 .field-input input {
  text-align: left;
  border-radius: 6rem;
  border: 1px solid #ffffff1a;
  padding: .6rem 2rem .6rem 1rem;
  width: 100%;
  transition: .5s;
  position: relative;
  margin-bottom: 16px;
  background-color: #0000004a;
  color: #cfcfc4;
}

 .field-input input:focus {
  outline: none;
  border-color: #3CA3F0;
  transition: .5s;
}
.field-input span {
    display: flex; 
   
     align-self: center; 
    padding: 6px;
    cursor: pointer;
    font-size: 18px;
    color: #ffffff3b;
    margin-bottom: 16px;
}
.field-input span:hover{
  color: white;
}



/* play ketframe */
.play-btn{
  color: white;
  font-size: 32px;

}

.floating-icon {
  display: none;
}


.i {
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
/*   margin: 20px auto;
  width: 50px; */
  /*height: 50px;*/
  /*background: white;*/
  border-radius: 5px;
  /*font-family: 'Montserrat', sans-serif;*/
  /*font-size: 20px;*/
  /*font-weight: lighter;*/
  letter-spacing: 2px;
  transition: 1s box-shadow;
}

.i {
  box-shadow: 0 5px 35px 0px rgba(0,0,0,.1);
}

.i:before, .i:after {
  display: block;
  content: '';
  position: absolute;
  width: 50%;
  height: 75%;
    /*padding: 13px;*/
  /*width:100%;
  height:100%;*/
  background-image: linear-gradient(to right, rgb(0, 242, 254) 0%, rgb(79, 172, 254) 100%);
  border-radius: 5px;
  z-index: -1;
  animation: 1s clockwise infinite;
  webkit-clip-path: polygon(100% 50%, 0 0, 0 100%);
  clip-path: polygon(100% 50%, 0 0, 0 100%);
  margin-top: 9px;
}

.i:after {
  background-image: linear-gradient(to right, rgb(79, 172, 254) 0%, rgb(0, 242, 254) 100%);
  animation: 1.5s counterclockwise infinite;
  margin-right: 18px;
}
.i:before {
  margin-left: 16px;
}

@keyframes clockwise {
  0% {
    top: -5px;
    left: 0;
  }
  12% {
    top: -2px;
    left: 2px;
  }
  25% {
    top: 0;
    left: 5px;    
  }
  37% {
    top: 2px;
    left: 2px;
  }
  50% {
    top: 5px;
    left: 0;    
  }
  62% {
    top: 2px;
    left: -2px;
  }
  75% {
    top: 0;
    left: -5px;
  }
  87% {
    top: -2px;
    left: -2px;
  }
  100% {
    top: -5px;
    left: 0;    
  }
}

@keyframes counterclockwise {
  0% {
    top: -5px;
    right: 0;
  }
  12% {
    top: -2px;
    right: 2px;
  }
  25% {
    top: 0;
    right: 5px;    
  }
  37% {
    top: 2px;
    right: 2px;
  }
  50% {
    top: 5px;
    right: 0;    
  }
  62% {
    top: 2px;
    right: -2px;
  }
  75% {
    top: 0;
    right: -5px;
  }
  87% {
    top: -2px;
    right: -2px;
  }
  100% {
    top: -5px;
    right: 0;    
  }
}




/*////////////////////////////////main////////////////////////////*/


/*main{
  height: 100%;
  width:100%;
  position: absolute;
}
*/
.main-layout__content{
  margin-top: 60px;
  margin-left: 70px;
}








@media (min-width: 320px) and (max-width: 767px) {
  
 /*top nav*/
 .profile_card{
  width: unset;
  margin-right: 10px;
 }
 .profile_card_conent{
  display: none;
 }
 .game-select{
  display: none;
 }
 .play-wrapper{
  margin-left: 0px;
 }
 
 .hamburger-menu {
  background: #1b2731;
  display: flex;
  width: 70px;
  justify-content: center;
  align-items: center;
}
.chat-sidebar{
  width: 100%;
  height: calc(100% - 60px);
  overflow: scroll;
}

.sidebar{
  display: none;
}
.notification{
 display: none;
}
.playtonia-logo{
  width: 40px;
}

.floating-icon {
    position: fixed;
    bottom: 25px;
    right: 25px;
    z-index: 3;
    display: block;
    /* width: 52px; */
    /* height: 52px; */
    font-size: 20px;
    color: white;
    padding: 10px;
    border-radius: 8px;
    background-image: linear-gradient(to right, rgb(79, 172, 254) 0%, rgb(0, 242, 254) 100%);
    
}



.main-layout__content{
 
  margin-left: 0;
}

.participants_card_title, .participants_card_discription{
  max-width: 180px;
}
}

</style>