---
title: Staff
nav_order: 6
---


<style>
.staff-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 30px;
}

/* Instructor section */
.instructor-box {
    text-align: center;
    width: 220px;
}

.instructor-box img {
    width: 160px;
    height: 160px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid #ccc;
}

/* Teaching Assistants Grid */
.ta-container {
    display: grid;
    grid-template-columns: repeat(2, 1fr); /* Creates a 2x2 grid */
    gap: 30px;
    justify-content: center;
}

.ta-box {
    text-align: center;
    width: 200px;
}

.ta-box img {
    width: 140px;
    height: 140px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid #ccc;
}
</style>

<!-- Instructor -->
<div class="staff-container">
    <div class="instructor-box">
        <img src="./images/staffs/Emami.png" alt="Dr. Seyyed Ali Emami Khansari">
        <h3>Dr. Seyyed Ali Emami Khansari</h3>
        <p>Instructor</p>
        <p><a href="mailto:emami@sharif.edu">Email</a></p>
    </div>

    <!-- Teaching Assistants -->
    <div class="ta-container">
        <!-- TA 1 -->
        <div class="ta-box">
            <img src="./images/staffs/Narimani.png" alt="Mohammad Narimani">
            <h3>Mohammad Narimani</h3>
            <p>Teaching Assistant</p>
            <p><a href="mailto:narimani@sharif.edu">Email</a></p>
        </div>

        <!-- TA 2 -->
        <div class="ta-box">
            <img src="./images/staffs/Shahrajabian.png" alt="Mahdi Shahrajabian">
            <h3>Mahdi Shahrajabian</h3>
            <p>Teaching Assistant</p>
            <p><a href="mailto:shahrajabian@sharif.edu">Email</a></p>
        </div>
    </div>
</div>
