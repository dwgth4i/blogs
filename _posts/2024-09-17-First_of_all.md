---
title: "Đôi lời về CPTS và CVE"
date: 2024-09-17
---

# CERTIFIED PENETRATION TESTER SPECIALIST
Quá trình mình học và thi rồi có kết quả chứng chỉ diễn ra từ 23/12/2023 đến 14/08/2024. Từ lúc bắt đầu học job role path của chứng chỉ này là mình đã học qua syllabus của OSCP và lớp REDTEAM OPERATOR của Cyberjutsu.

![image](https://gist.github.com/user-attachments/assets/63dff4f7-7556-44fb-9668-77aa63c30619)

Về quá trình học thì mình thấy họ dạy khá kĩ về basic web vuln và Active Directory, cũng sẽ là 2 phần khó nhất của bài exam (đối với mình). Do học qua khoảng thời gian tết rồi thi học kì blah blah nên cũng khá delay, tận 6 tháng mình mới xong hết penetration tester job role path để có thể đăng kí thi.

![image](https://gist.github.com/user-attachments/assets/a776a248-2ede-4515-a103-92cc26ec6176)

![image](https://gist.github.com/user-attachments/assets/808051fa-86ef-4236-bd1f-3c26f04f1db2)

Trước khi thi thật thì họ cũng khuyên nên làm qua 2 prolabs là Dante (easy) và Zephyr (Medium), với mình thì thật sự về kĩ thuật thì sẽ không quá khó, học hết path kia là đã có thể làm được full Dante và tầm 90% Zephyr rồi và mình đã làm được full cả 2 prolabs này (flex tí hehe), nhưng mà đến lúc thi thật thì do áp lực nên khá ngợp, phải mất 1,5 ngày đầu tiên mình mới tìm ra được flag đầu tiên trong khi phải 12/14 flag thì mới pass nên trong thời gian thi ngày nào mình cũng ngồi hack 15 tiếng cực kì mệt và căng thẳng, liên tục rơi vào khoảng bế tắc mà không nghĩ được thêm gì. Nên là dưới đây sẽ là tips của mình cho những bạn nào định thi:
- Sẽ có 2 lần thi nên hãy tưởng tượng bạn có 20 ngày thi liền (mỗi lần thi 10 ngày) nếu như lần đầu trượt, nên không có gì phải vội cả, đừng cố quá.
- Kiến thức thì học xong path là đủ, nếu làm nhiều lab với box rồi cả web thì sẽ càng tốt (nhất là web).
- Ăn uống ngủ nghỉ 

# CVE đầu tiên
Do bị khịa khá nhiều nên mình quyết định đi tìm CVE :v nhưng mà kể cả là "CVE cỏ" đi thì cảm giác là tác giả của cái gì đó, là "người đầu tiên tìm ra lỗ hổng" trong chương trình nào đó cũng sướng thật =))). Khoảng trong 1 tuần, mình đi tìm các open-source project để tìm bug và submit khá nhiều vendor thì được 2 CVE trên vuldb (còn vài cái đang pending nữa). Tuy khá là cỏ nhưng mà ít ra cũng có động lực để sau này tìm được CVE đỏ, đỡ dính mác CVE cam :((

Việc tìm được CVE cũng nhờ phần lớn do 1 người anh đi trước giúp đỡ, không phải giúp mình tìm bug mà giúp mình boost thêm tự tin bằng cách ném cho 1 thằng open-source mà anh ấy tìm được bug rồi nhưng xong rồi để mình tự tìm =)) và đúng là mình tìm ra được thật và setup tấn công các thứ như thật. Từ đó giúp mình tự tin hơn mà cho mình vài tips để tiếp tục trên con đường gia nhập clb những người có CVE =)))

# Kết bài

Đến đây thì hết rồi, những bước chân đầu tiên vào nghề, được gặp gỡ các người anh, mentor xuất sắc trong ngành là điều mình cảm thấy khá là may mắn hay còn gọi là chọn đúng nền văn minh:)  