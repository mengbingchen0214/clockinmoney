# salary-clock                                                             
                                                                                
  > A real-time salary tracker that shows you exactly how much money you're     
  earning — second by second.                                                   
                                                                                
  **Live Demo:** [mengbingchen0214.github.io/clockinmoney](https://mengbingchen0
  214.github.io/clockinmoney)
                                                                                
  ---                                                                        

  ## What it does

  You're at work. Every second that passes, you're earning money. This tool     
  makes that visible.
                                                                                
  Enter your monthly salary, daily work hours, and working days per month — then
   hit **Start Work**. Watch your earnings accumulate in real time, down to the
  fraction of a cent. Clock out when your shift ends to see your total for the  
  day.                                                                       

  ## Features

  - **Real-time earnings counter** — updates every second, displayed to 4       
  decimal places
  - **Zero dependencies** — pure HTML/CSS/JS, runs entirely in your browser     
  - **Mobile-friendly** — responsive design works on any screen size            
  - **Animated UI** — falling coins, glow effects, and a satisfying end-of-day
  summary screen                                                                
                                                                             
  ## Usage                                                                      
                                                                             
  No install needed. Just open `index.html` in any browser.                     
  
  1. Enter your **monthly salary** (¥)                                          
  2. Set your **daily work hours** (e.g. 8)                                  
  3. Set your **working days per month** (e.g. 22)                              
  4. Click **Start Work** — your earnings start counting
  5. Click **Exit Work** when done to see your daily total                      
                                                                             
  ### Formula                                                                   
                                                                             
  ```                                                                           
  earnings per second = monthly salary ÷ (working days × daily hours × 3600) 
  ```

  ## Why this exists                                                            
  
  Sometimes you need a reminder that every minute you spend at work has tangible
   value. This tool makes that concrete and real-time — a small motivational 
  nudge to get through the day.                                                 
                                                                             
  ## Tech stack

  - Plain HTML, CSS, JavaScript                                                 
  - Canvas API for background animation
  - No frameworks, no build step, no dependencies                               
                                                                                
  ## License
                                                                                
  MIT             
 
 忍住就是赢 · 上班赚钱计时器

  每一秒都在赚钱 💰

  输入你的月薪、每天工作时长、每月工作天数，实时显示
  今天已赚了多少钱。

  使用方法

  1. 填写你的月薪
  2. 填写每天工作时长
  3. 填写每月工作天数
  4. 点击「开始上班」
  5. 下班时点「下班」，查看今日收益
