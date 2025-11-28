🐱 SuduList | 单文件智能任务管理器
A Smart Task Manager in One HTML File


(等一等会加载出gif演示图）



*     我将会超级高频的持续更新这个程序，喜欢的话记得帮我点个star～，这对我非常重要


✨ 为什么选择 SuduList？
作为一个由学生开发的单文件工具，它把「智能」和「简单」结合得刚刚好：


![2025-11-1820 22 51-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/fc445de6-129f-4f64-858d-8bae03fda99d)

* 		仅 1 个 HTML 文件：无需安装，双击即用，手机 / 电脑都能跑，数据存在本地不丢失
* 		AI 级时间识别：输入 “明天下午 3 点交作业”，自动解析时间并安排，不用手动选日期
* 		效率拉满的快捷操作：一键标记优先级（高 / 中 / 低）、拖拽调整时间，操作比记笔记还快
* 		贴心统计与提醒：自动生成任务完成率图表，到期前弹窗提醒，再也不怕忘事
* 		自定义到细节：主题色、字体大小、动画速度都能改，你的工具你说了算
* 		还有猫助手加持：累了会给你发加油语录（比如 “今天也超努力的！休息 5 分钟再冲吧～”）
🚀 核心功能速览
✅ 智能时间解析 | 输入带时间的句子自动识别并归档，输入自然的语言例如“明天午上课”系统智能识别

![演示](https://github.com/user-attachments/assets/e0e33a5b-ec92-4045-a596-4f6f9be5c23d)

✅ 优先级快捷设置 | 点一下标记重要任务，颜色区分一目了然


✅ 任务统计看板｜查看往日任务展示完成情况，智能任务分析成就感可视化


![2025-11-1820 22 51-ezgif com-video-to-gif-converter-2](https://github.com/user-attachments/assets/4b1d753d-5131-41bf-ae83-c25f009424ae)


✅ 到期提醒 | 浏览器弹窗 + 桌面通知（需授权），不怕遗漏


✅ 高度自定义设置｜时间关键词，繁忙时间由你设定


![2025-11-1820 22 51-ezgif com-video-to-gif-converter-3](https://github.com/user-attachments/assets/d4b10a7c-6f76-46c8-8f3e-43334d28e06e)


✅ 猫助手互动 | 随机掉落鼓励语录，分析完成情况，学习工作不枯燥（还有超级带感的摸摸功能）


![2025-11-1820 22 51-ezgif com-video-to-gif-converter-3](https://github.com/user-attachments/assets/307aa280-bd4b-46c2-9d4d-29079586db38)


✅支持中英文双语（英文模式会有小bug）



🔍 如何使用？
* 		点击仓库里的 sudulist.html
* 		点击右上角 Raw 按钮，跳转到纯文件页面
* 		右键保存到电脑，用任意浏览器打开即可 （手机用户：保存后用 Chrome/Edge 等浏览器打开，建议添加到桌面更方便）


📝 开发说明
* 		我是一名学生，这是我的第一个开源小项目，代码可能有不完美的地方，遇到 Bug 请在 Issues 里告诉我，会努力修复～
* 		部分功能（如时间识别逻辑）由 AI 辅助实现，已检查无抄袭，欢迎大家一起优化代码～


🎯 未来想加的功能
* 		🔜 增加子任务功能（比如 “写论文” 包含 “查资料 + 写提纲”）
* 		🔜 猫助手语录自定义（可以添加自己的加油话）
*             🔜 支持英文自然语言输入


更新日志：
11.18 v1.0.4 修复了很多英文模式下的bug


11.19 v1.0.5 大大优化了整体性能：

             新增防抖机制：针对任务统计、智能建议、图表渲染等设置差异化延迟，减少无效计算与 DOM 操作
             
             优化 Storage 缓存系统
             
             强化 DOM 元素缓存,避免重复渲染
             
             规范定时器管理，节省 CPU 资源并防止内存泄漏
             

11.19 v1.0.6 任务详情和任务冲突界面出现了许多错误的翻译键，暂时强制在这两个页面强制切为中文

             在设置中增加了自动忽略冲突的功能
             
             修复了在快捷调整时间时会一抖一抖的bug
             

11.20 v1.0.7 修复了新手引导页面图标消失和图层不对的问题

             对设置界面的性能进行优化避免了卡顿
             
             修复了自动忽略冲突的设置不生效的问题
             
             增加了冲突界面按下enter可以直接智能调整时间的功能
             
             修复了出现冲突弹窗解决后上一次输入的任务仍保留在输入框内的问题
             
             增加更多时间识别关键词，例如“明早”“明晚”
             
             增大了快速待办的确认按钮方便点击


11.23 v1.0.8 删除了一些多余的由bug导致的小图标   

             将快速待办栏的滚轮删除并直接排列显示，更加方便直观地查看任务
             
             将一些模块样式改为圆角
             
             一些不值得一提的小完善


11.28 v1.0.9 保持输入框置顶方便使用

             在按下回车后输入焦点会继续保持在输入框内以便连续添加任务

             将一些模块样式统一为圆角

             添加了如果没有精确时间则自动设置为早上的设定

             启动速度和一些小优化

            

 SuduList | Single-file Intelligent Task Manager A Smart Task Manager in One HTML File
✨ Why choose SuduList?
As a single-file tool developed by students, it combines "intelligence" and "simplicity" perfectly: 

*     Just 1 HTML file: No installation required. Double-click to use. Works on both mobile and computer. Data is stored locally and won't be lost.
*     AI-level time recognition: Input "Submit homework at 3 PM tomorrow afternoon", the system automatically parses the time and schedules it. No need to manually select the date.
*     Efficient and powerful quick operations: Mark priority levels (high / medium / low) with one click, drag to adjust time. The operation is even faster than taking notes.
*     Thoughtful statistics and reminders: Automatically generate task completion rate charts, pop-up reminders before the due date. No longer afraid of forgetting.
*     Customizable to the details: Theme color, font size, animation speed can all be changed. Your tool is up to you.
*     Enhanced with Cat Assistant: When tired, it will send you motivational quotes (such as "I also worked super hard today! Take a 5-minute break and keep going~")
core Function Overview

✅ Intelligent time parsing | Input sentences with time and the system automatically recognizes and archives them. The system can intelligently recognize sentences like "Class at noon tomorrow afternoon" 

✅ Quick Priority Setting | Just click to mark important tasks, and the colors clearly distinguish them. 

✅ Task Statistics Dashboard | View the completion status of past tasks, conduct intelligent task analysis, and visualize the sense of achievement 

✅ Expiry Reminder | Browser pop-up + Desktop notification (requires authorization), no worries about missing any. 

✅ Highly customizable settings | Time keywords, set your own busy hours 

✅ Cat Assistant Interaction | Randomly drop encouragement quotes, analyze completion status, and make learning and work not boring (and there's also a super cool touching function) 

✅ Supports bilingual (Chinese and English) (There may be minor bugs in the English mode)
    nterface preview ! [Demo](https://github.com/user-attachments/assets/9cf27cfe-970b-4b24-a623-f4f0e2cb612d) 
    ow to use?
    
*     Click on sudulist.html in the repository
*     Click the Raw button on the top right corner to jump to the pure file page
*     Right-click and save to your computer. Open it with any browser (mobile users: Open with Chrome/Edge or other browsers after saving. It is recommended to add it to your desktop for convenience)


   Development Notes
  
*     I am a student. This is my first open-source small project. The code may have some imperfect parts. If you encounter bugs, please tell me in the Issues section and I will try to fix them.
*     Some functions (such as time recognition logic) are assisted by AI. It has been checked for plagiarism. Welcome everyone to optimize the code together.


   Future Features to Add

  
*     🔜 Add sub-task function (for example, "Write a thesis" includes "Search for materials + Write an outline")
*     🔜 Customize cat assistant quotes (you can add your own motivational words)
*     🔜 Support for natural language input in English


stack + browser compatibility list—great for students to learn, developers to fork & customize—open-source spirit at its best!


11.18 v1.0.4 has fixed many bugs in the English mode. Now, using the English mode will no longer cause any major problems. 


11.19 v1.0.5 significantly improved the overall performance:
             Added a debounce mechanism: Differentiated delays were set for task statistics, intelligent suggestions, and chart rendering. The task rendering was doubly protected to reduce invalid calculations and DOM operations.
             Optimized the Storage cache system: Memory caching, batch saving, and debounce writing.
             Strengthened DOM element caching: Common nodes and task elements were cached, and repeated rendering was avoided through state checks.
             Standardized timer management: Centralized control + page hiding pause + automatic cleaning, saving CPU resources and preventing memory leaks.



11.19 v1.0.6 There were many incorrect translation keys in the task details and task conflict interface. For the time being, we have temporarily forced the switching to Chinese on these two pages.
           The function of automatically ignoring conflicts has been added in the settings.
           The bug that caused jittering when adjusting the time quickly has been fixed.



