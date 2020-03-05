
# project git 
## create project and command git basic to github

1.drop-down menu, and select New repository

![GitHub Logo](https://help.github.com/assets/images/help/repository/repo-create.png)
  
2.Choose a template drop-down and select a template repository
  ![GitHub Logo](https://help.github.com/assets/images/help/repository/template-drop-down.png)

3.Use the Owner drop-down menu, and select the account you want to own the repository
  ![GitHub Logo](https://help.github.com/assets/images/help/repository/create-repository-owner.png)
  
  4.Type a name for your repository, and an optional description
  ![GitHub Logo](https://help.github.com/assets/images/help/repository/create-repository-name.png)
  5.Choose a repository visbility. For more information, see "About repository visibility."
  ![GitHub Logo](https://help.github.com/assets/images/help/repository/create-repository-public-private.png)

commands git basic

Git และ Github คืออะไร
Git คือ Version control ที่คอยจัดเก็บความเปลี่ยนแปลงของไฟล์ในโปรเจคของเราหรือของทีมเราไม่ว่าเพื่อนคนไหนจะเปลี่ยนแปลง, เพิ่ม, ลบอะไรในโปรเจคเราก็สามารถที่จะรับรู้ได ้ทำให้รู้ว่า ‘งานที่กำลังทำอยู่ถึงไหนแล้ว’
  Github คือ เว็ปไซต์ที่ทำให้เราสามารถใช้ Git ร่วมกับคนอื่นได้ หรือพูดง่ายๆก็คือ Git ที่อยู่บนเว็บไซต์นั่นแหละก็อย่าลืมสมัครก่อนอ่านขั้นตอนการใช้ต่อไปด้วยล่ะ
  การใช้งาน Git หลังจากที่ดาวโหลดมาเสร็จแล้วเข้าไปที่ Terminal (Windows เข้าผ่าน git-bash.exe)(แต่ละคนอาจจะไม่เหมือนกันแต่ใช้พิมพ์ได้ก็พอ) หลังจากนั้นลองพิม git — version แล้วก็ทำการ Setup git เพื่อให้จำ email และชื่อของเราเป็นอันสำเร็จสำหรับการ config เบื้องต้น
  
  1.git add <filename>, git add * (add all files) เพิ่มไฟล์เข้า index
  
  2.git commit -m “message” เขียนเพื่อบอกอัพเดทแต่ละที
  
  3.git push origin master อัพเดทกิ่ง master ใน Repository
  
  4.git pull origin master เพื่ออัพเดทข้อมูลใน local ให้เท่ากับใน Repository
  
  คำสั่งที่ใช้บ่อยที่สุดก็จะมีประมาณนี้ แต่ถ้าต้องการศึกษาเพิ่มเติมก็จะมีอีกหลายคำสั่งที่สำคัญๆ เช่น git merge, git checkout ,git branch , git diff, git blame และอีกมากมายถ้าต้องการศึกษาเพิ่มเติม git — the simple guide  
  ![GitHub Logo](https://rubygarage.s3.amazonaws.com/uploads/article_image/file/599/git-cheatsheet-5.jpg)