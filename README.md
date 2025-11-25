## 👋 Xin chào!

<!-- Tạo phần giới thiệu nhấp nháy -->
<p align="center">
  <span class="typewriter">
    Hi tôi là Nguyễn Văn Tuấn Minh. Sinh viên năm 2 Trường Đại Học Phương Đông.
  </span>
  <span class="typewriter-jp" style="display:none;">
    私はグエン・ヴァン・トゥアン・ミンです。フォンドン大学の情報技術学部の二年生です。
  </span>
</p>

<style>
/* Hiệu ứng gõ chữ */
.typewriter, .typewriter-jp {
  font-size: 18px;
  font-weight: bold;
  border-right: 2px solid #F85D7F;
  white-space: nowrap;
  overflow: hidden;
  width: 0;
  display: inline-block;
  animation: typing 4s steps(50, end) forwards;
}

@keyframes typing {
  from { width: 0; }
  to { width: 100%; }
}

/* Hiệu ứng đổi câu */
</style>

<script>
let sentences = [
  "Hi tôi là Nguyễn Văn Tuấn Minh. Sinh viên năm 2 Trường Đại Học Phương Đông.",
  "私はグエン・ヴァン・トゥアン・ミンです。フォンドン大学の情報技術学部の二年生です。"
];

let current = 0;
const typewriter = document.querySelector(".typewriter");
const typewriterJP = document.querySelector(".typewriter-jp");

function showNextSentence() {
  if(current % 2 === 0){
    typewriter.style.display = "inline-block";
    typewriterJP.style.display = "none";
  } else {
    typewriter.style.display = "none";
    typewriterJP.style.display = "inline-block";
  }
  
  // Reset animation
  let el = current % 2 === 0 ? typewriter : typewriterJP;
  el.style.animation = "none";
  void el.offsetWidth; // trigger reflow
  el.style.animation = "typing 4s steps(50, end) forwards";
  
  current = (current + 1) % sentences.length;
  setTimeout(showNextSentence, 5000); // 5s cho mỗi câu
}

window.onload = () => {
  showNextSentence();
}
</script>


## 👨‍🎓 Giới thiệu
- **Họ tên**: Nguyễn Văn Tuấn Minh
- **Sinh viên năm 2** – Đại học Phương Đông  
  Chuyên ngành: **Công nghệ Thông tin**
- Đang nỗ lực từng ngày để trở thành Full-stack Developer
- Đặc biệt yêu thích văn hóa và công nghệ Nhật Bản 🇯🇵

## 🌐 Ngôn ngữ
- 🇻🇳 Tiếng Việt – Native
- 🇯🇵 Tiếng Nhật – JLPT **N4** (đang ôn N3 thật chăm chỉ)
- 🇬🇧 Tiếng Anh – Đọc tài liệu, comment code ổn

## 🛠 Kỹ năng công nghệ
| Lĩnh vực       | Công nghệ                                      | Trình độ       |
|-----------------|------------------------------------------------|----------------|
| Backend         | PHP (Laravel cơ bản), Java (Spring Boot cơ bản)| Trung bình     |
| Frontend        | HTML, CSS, JavaScript, Bootstrap               | Trung bình - Khá |
| Database        | SQL Server, MySQL                              | Trung bình - Khá |
| Tools           | Git, GitHub, VS Code, Postman, XAMPP           | Thành thạo     |

🔭 Hiện đang học thêm: Laravel, Spring Boot, React cơ bản

## 🚀 Một số dự án nổi bật

<details open>
  <p align="center">
    <a href="https://github.com/minhangry/ogc.git">
      <img width="278" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=minhangry&repo=ogc&theme=tokyonight&bg_color=1F222E&title_color=F85D7F&hide_border=true&icon_color=F8D866&show_icons=false" />
    </a>
  </p>
</details>





## 🎌 Mục tiêu đến 2026
- JLPT **N3** trước tháng 7/2026
- JLPT **N2** trước khi ra trường
- Có ít nhất 1 dự án thực tế được deploy online
- Thực tập tại công ty Nhật hoặc công ty Việt-Nhật

## 📫 Liên hệ mình
- Email: minhmissu@gmail.com 
- Zalo: 0346182006 

> "一日一歩" – Mỗi ngày tiến một bước nhỏ, mình sẽ đi được rất xa!  
Cảm ơn bạn đã ghé thăm profile nhé ✨

⭐ Nếu thấy hay thì cho mình 1 star nha!
<p align="center">
  <!-- Total Stars -->
  <a href="https://github.com/minhangry?tab=repositories&sort=stargazers">
    <img alt="Total Stars" title="Tổng số stars nhận được" 
         src="https://custom-icon-badges.demolab.com/github/stars/minhangry?color=55960c&style=for-the-badge&labelColor=488207&logo=star" />
  </a>

  <!-- Followers -->
  <a href="https://github.com/minhangry?tab=followers">
    <img alt="Followers" title="Follow mình trên GitHub" 
         src="https://custom-icon-badges.demolab.com/github/followers/minhangry?color=236ad3&labelColor=1155ba&style=for-the-badge&logo=person-add&label=Follow&logoColor=white" />
  </a>

  <!-- Profile Views – fix mới, load 100%, giống ảnh bạn gửi -->
  <a href="https://github.com/minhangry/minhangry">
    <img alt="Profile Views" title="Số lượt xem profile" 
         src="https://komarev.com/ghpvc/?username=minhangry&color=8B46FF&style=for-the-badge&label=VISITORS&labelColor=6B2D5C&logo=eye&logoColor=white" />
  </a>
</p>
