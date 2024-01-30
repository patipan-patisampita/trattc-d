<template>
    <div class="container my-4">
        <div class="row">

            <div class="col-md-3">
                <div class="card shadow p-2">
                    <div class="card-header p-0">
                        <img src="../assets/images/kitjakam.png" class="card-img-top" alt="img">
                    </div>
                    <div class="card-body text-center">
                        <span class="card-title" style="color: #FF8C00; font-size: 18px;">นายปรีชา ปานกลาง</span>
                        <p class="card-text" style="color: #006400; font-size: 17px;">รองผู้อำนวยการ
                            ฝ่ายพัฒนากิจการนักเรียน-นักศึกษา</p>
                    </div>
                </div>
            </div>

            <div class="col-md-9">
                <div class="card">
                    <div class="card-body">
                        <h5 class="font-weight-normal mt-1" style="color: #006400;">หน้าที่และความรับผิดชอบ</h5>
                        <p class="mb-4">รองผู้อำนวยการฝ่ายพัฒนากิจการนักเรียน นักศึกษา มีหน้าที่และความรับผิดชอบ
                            และลักษณะงานที่ปฏิบัติรองจากผู้อำนวยการวิทยาลัยฯ
                            โดยปฏิบัติงานตามที่ได้รับมอบหมายจากผู้อำนวยการวิทยาลัยฯ ในการช่วยบริหารกิจการของสถานศึกษา
                            การวางแผนการปฏิบัติงาน การควบคุม กำกับ ดูแล งานกิจกรรมนักเรียน นักศึกษา งานครูที่ปรึกษา
                            งานปกครอง งานแนะแนวอาชีพและจัดหางาน งานสวัสดิการนักเรียนนักศึกษา
                            งานโครงการพิเศษและการบริการชุมชน และงานอื่นที่เกี่ยวข้อง โดยช่วยปฏิบัติราชการในเรื่องต่อไปนี้.
                        </p>
                    </div>
                    <div class="card-header p-0 position-relative mt-n4 mx-3 z-index-2">
                        <ol type="square">
                            <li>บริหารกิจการสถานศึกษาให้เป็นไปตามกฎหมาย ระเบียบ ข้อบังคับ นโยบายและวัตถุประสงค์ของสถานศึกษา
                            </li>
                            <li>วางแผนพัฒนาการศึกษา ประเมิน และรายงานผลการจัดการศึกษา</li>
                            <li>จัดทำและพัฒนาหลักสูตรสถานศึกษา การจัดกระบวนการเรียนรู้ การพัฒนาสื่อ นวัตกรรม
                                และเทคโนโลยีทางการศึกษา การนิเทศ และการวัดผลประเมินผล</li>
                            <li>ส่งเสริมและจัดการศึกษา ฝึกอบรมให้กับผู้เรียนทุกกลุ่มเป้าหมายทั้งในระบบ นอกระบบและตามอัธยาศัย
                            </li>
                            <li>จัดทำระบบประกันคุณภาพการศึกษา</li>
                            <li>การบริหารการเงิน การพัสดุ และทรัพย์สินอื่น</li>
                            <li>วางแผนการบริหารงานบุคคล การสรรหา การบรรจุ แต่งตั้ง การเสริมสร้างประสิทธิภาพในการปฏิบัติงาน
                                วินัย การรักษาวินัย การดำเนินการทางวินัย และการออกจากราชการ</li>
                            <li>จัดทำมาตรฐานและภาระงานของข้าราชการครูและบุคลากรทางการศึกษาในสถานศึกษา
                                ประเมินผลการปฏิบัติงานตามมาตรฐานของข้าราชการครูและบุคลากรทางการศึกษา</li>
                            <li>ส่งเสริมสนับสนุนบุคลากรในสถานศึกษาให้มีการพัฒนาอย่างต่อเนื่อง</li>
                            <li>ประสานความร่วมมือกับชุมชนและท้องถิ่นในการระดมทรัพยากรเพื่อการศึกษาและให้บริการวิชาชีพแก่ชุมชน
                            </li>
                            <li>จัดระบบควบคุมภายในสถานศึกษา</li>
                            <li>จัดระบบดูแลช่วยเหลือผู้เรียน</li>
                            <li>ปฏิบัติงานอื่นตามที่ได้รับมอบหมาย</li>
                        </ol>
                    </div>
                </div>
            </div>

        </div>
    </div>
</template>

<script setup>
import { toast } from 'vue3-toastify';
import 'vue3-toastify/dist/index.css';

toast.success("ยินดีต้อนรับ ฝ่ายพัฒนากิจการนักเรียน นักศึกษา", {
    autoClose: 1500,
    position: toast.POSITION.TOP_CENTER,
})

const notify = () => {
    toast.info("ยินดีต้อนรับ ฝ่ายพัฒนากิจการนักเรียน นักศึกษา", {
        autoClose: 1500,
    })
    return notify
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Sarabun&display=swap');

.navbar {
    font-family: 'Sarabun', sans-serif;
    font-size: 14px;
}

.dropdown-item {
    font-size: 14px;
}

.card-text {
    font-family: 'Sarabun', sans-serif;
    font-size: 14px;
}

.card-title {
    font-family: 'Sarabun', sans-serif;
}

h5 {
    font-family: 'Sarabun', sans-serif;
}

p {
    font-family: 'Sarabun', sans-serif;
    font-size: 14px;
}

ol {
    font-family: 'Sarabun', sans-serif;
    font-size: 16px;
}

.nav-link {
    font-family: 'Sarabun', sans-serif;
    font-size: 14px;
}</style>