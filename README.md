# midterm_887342
พื้นฐานเกี่ยวกับ Version control และ git
11. ประโยชน์ของ version control 
คือ 1สามารถเรียกดู Version ไหนก็ได้ตามที่ต้องการ 
2สามารถทำงานร่วมกันเป็นทีมได้สะดวก
3.สามารถติดตามหรือดูการเปลี่ยนแปลงหรือแก้ไขที่ผ่านมาได้ตลอดเวลา
4.นักพัฒนาสามารถเป็นเจ้าของ Branch ในตำแหน่งต่างๆได้

12. . ข้อได้เปรียบของ Distributed Version control เมื่อเทียบกับ Centralized version control
1.นักพัฒนาคนอื่นๆสามารถเป็นเจ้าของ Repo และสามารถพัฒนา Repoของคนอื่นต่อได้
2.กระบวนการดำเนินธุรกิจในปัจจุบัน เป็นลักษณะการกระจายการทำงานไปยังสถานที่ต่างๆ 
3. การกระจายการทำงานทำให้ข้อมูล ข่าวสาร และบริการต่าง ๆ ใกล้ชิดกับผู้ใช้ หรือลูกค้ามากขึ้น
4. ราคาของเครื่องพิวเตอร์ และอุปกรณ์เครือข่ายถูกลง 


13. ข้อได้เปรียบของ Centralized Version control เมื่อเทียบกับ Distributed version control
1ทุกคนสามารถเชื่อมต่อแหละเช็คข้อมูลได้ จาก Main trunk
2จัดการง่าย สะดวกรวดเร็ว
3 มีความปลอดภัยของข้อมูลสูง

14.บอกแนวทางในการแก้ไข conflict ที่เกิดขึ้นเมื่อมีการ merge โปรแกรมของผู้พัฒนาพร้อมกันหลายๆคน
ตอบ 1.Mob programing แก้ปัญหา Merge conflict ได้ 100 เปอร์เซนต์ เนื่องจากทุกคนมาทำงานพร้อมกันเครื่องเดียวกัน

15.บอกแนวทางในการลด conflict ที่เกิดขึ้นเมื่อมีการ merge โปรแกรมของผู้พัฒนาพร้อมกันหลายๆคน
1.ในหนึ่ง class หนึ่ง Method นั้นควรมีเหตุผลเดียวในการเปลี่ยนแปลง เพื่อจะช่วยลดปัญหาที่ในการแก้ไขต่างๆ
2. หลีกเลี่ยงปัญหาโดยการ Merge บ่อยๆ ทุกครั่งที่มีการทำหรือเปลี่ยนแปลง หรือ Commit Code จะช่วยลดปัญหาขัดแย้งดังกล่าวได้

16.git คือ 
Version Control ตัวหนึ่ง ซึ่งเป็นระบบที่มีหน้าที่ในการจัดเก็บการเปลี่ยนแปลงของไฟล์ในโปรเจ็คเรา มีการ backup code ให้เรา สามารถที่จะเรียกดูหรือย้อนกลับไปดูเวอร์ชั่นต่างๆของโปรเจ็คที่ใด เวลาใดก็ได้ หรือแม้แต่ดูว่าไฟล์นั้นๆใครเป็นคนเพิ่มหรือแก้ไข หรือว่าจะดูว่าไฟล์นั้นๆถูกเขียนโดยใครบ้างก็สามารถทำได้ ฉะนั้น Version Control ก็เหมาะอย่างยิ่งสำหรับนักพัฒนาไม่ว่าจะเป็นคนเดียวโดยเฉพาะอย่างยิ่งจะมีประสิทธิภาพมากหากเป็นการพัฒนาเป็นทีม 
แตกต่างจาก github คือ github จะเป็นเว็บไซต์ที่ให้บริการเสมือน git server เป็นบริการฟรีแบบมีเงื่อนไข คุณสามารถใช้งานได้ฟรี แต่โปรเจ็กที่สร้างขึ้นจะต้องเป็นแบบ public เท่านั้น คือ คนอื่นสามารถเข้าไปดูโค้ด ดูดโค้ด ท่านได้ ถ้าไม่อยากให้ชาวบ้านเห็นโปรเจ็กของท่าน ก็ต้องเสียตังใช้บริการ เพื่อสร้างโปรเจ็กแบบ private

17.จุดประสงค์หลักในการ Branch คือ
การแบ่งหน้าที่การทำงานใน Commit เหล่านี้โดยที่  default ของ branch ใน Git คือ master

18 Fast forward merge คืออะไร และทำไมการ push ไปที่ Remote repo จึงควรจะต้อง merger แบบนี้

19 หน้าที่หลักของคำสั่ง git pull คืออะไร
 คือการรวม code จาก remote มายัง local โดนที่เราไม่สามรถรู้ได้เลยว่าจะรวมโค๊ดอะไรบ้างรู้แค่หลังจาก pull เสร็จแล้วนั้นเอง ซึ่งจริงๆแล้ว git pull คือการทำ git fetch และต่อด้วย git merge

20 แผนภาพด้านล่างต่างการสื่อความหมายอะไร
ลักษะการทำงานของคำสั่ง Branch
