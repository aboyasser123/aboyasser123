<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>أحمد الحمّود | مطور ويب</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;600;700&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Cairo', sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: #f0f0f0;
            line-height: 1.6;
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .container {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 30px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
            border: 1px solid rgba(255, 255, 255, 0.1);
            margin-bottom: 30px;
        }
        
        header {
            text-align: center;
            padding: 40px 20px;
            background: linear-gradient(145deg, #2c5364, #2193b0);
            border-radius: 15px;
            margin-bottom: 30px;
        }
        
        h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            background: linear-gradient(45deg, #12c2e9, #c471ed, #f64f59);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
        }
        
        h2 {
            font-size: 2rem;
            margin: 25px 0 15px;
            color: #4fc3f7;
            border-right: 5px solid #4fc3f7;
            padding-right: 15px;
        }
        
        h3 {
            font-size: 1.5rem;
            margin: 20px 0 10px;
            color: #29b6f6;
        }
        
        p {
            margin-bottom: 15px;
            font-size: 1.1rem;
        }
        
        .badges {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 20px 0;
            justify-content: center;
        }
        
        .badge {
            background: linear-gradient(145deg, #2c5364, #2193b0);
            padding: 8px 15px;
            border-radius: 20px;
            font-weight: 600;
            display: flex;
            align-items: center;
            gap: 5px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        
        .badge:hover {
            transform: translateY(-3px);
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            margin: 25px 0;
        }
        
        .skill-category {
            background: rgba(41, 182, 246, 0.1);
            padding: 20px;
            border-radius: 15px;
            border: 1px solid rgba(41, 182, 246, 0.2);
        }
        
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 25px;
            margin: 25px 0;
        }
        
        .project {
            background: rgba(255, 255, 255, 0.05);
            padding: 20px;
            border-radius: 15px;
            transition: transform 0.3s;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .project:hover {
            transform: translateY(-5px);
            background: rgba(255, 255, 255, 0.08);
        }
        
        .stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 25px 0;
        }
        
        .stat-box {
            background: rgba(41, 182, 246, 0.1);
            padding: 20px;
            border-radius: 15px;
            text-align: center;
            border: 1px solid rgba(41, 182, 246, 0.2);
        }
        
        .stat-number {
            font-size: 2.5rem;
            font-weight: 700;
            background: linear-gradient(45deg, #12c2e9, #c471ed);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        .contact-links {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            justify-content: center;
            margin: 30px 0;
        }
        
        .contact-link {
            display: flex;
            align-items: center;
            gap: 8px;
            padding: 12px 25px;
            background: linear-gradient(145deg, #2c5364, #2193b0);
            color: white;
            text-decoration: none;
            border-radius: 30px;
            font-weight: 600;
            transition: all 0.3s;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        .contact-link:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
        }
        
        .quote {
            text-align: center;
            font-style: italic;
            margin: 30px 0;
            padding: 20px;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 15px;
            border-right: 5px solid #c471ed;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2.2rem;
            }
            
            h2 {
                font-size: 1.7rem;
            }
            
            .skills-grid, .projects, .stats {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>أحمد الحمّود</h1>
            <p>طالب هندسة معلوماتية | مطور ويب | مصمم واجهات</p>
            <div class="badges">
                <div class="badge">🎓 جامعة حلب</div>
                <div class="badge">💻 مطور ويب</div>
                <div class="badge">📱 Flutter</div>
            </div>
        </header>

        <section>
            <h2>نبذة عني</h2>
            <p>أنا <strong>أحمد الحمّود</strong>، طالب هندسة معلوماتية في <strong>جامعة حلب</strong>، شغوف بتطوير الويب وتصميم تجارب المستخدم. أسعى دائمًا لاكتساب مهارات جديدة والمشاركة في مشاريع مبتكرة.</p>
            
            <div class="quote">
                "التقنية ليست مجرد أدوات، بل هي فن صناعة المستقبل"
            </div>
        </section>

        <section>
            <h2>المهارات التقنية</h2>
            <div class="skills-grid">
                <div class="skill-category">
                    <h3>💻 لغات البرمجة</h3>
                    <p>C++ • Java • PHP • Dart • JavaScript</p>
                </div>
                <div class="skill-category">
                    <h3>🌐 تطوير الويب</h3>
                    <p>HTML • CSS • JavaScript • PHP • MySQL</p>
                </div>
                <div class="skill-category">
                    <h3>📱 Mobile Development</h3>
                    <p>Flutter • Dart</p>
                </div>
                <div class="skill-category">
                    <h3>🗄️ قواعد البيانات</h3>
                    <p>MySQL • SQL Server</p>
                </div>
            </div>
        </section>

        <section>
            <h2>إحصائيات GitHub</h2>
            <div class="stats">
                <div class="stat-box">
                    <div class="stat-number">15+</div>
                    <p>المشاريع المنفذة</p>
                </div>
                <div class="stat-box">
                    <div class="stat-number">500+</div>
                    <p>المساهمات</p>
                </div>
                <div class="stat-box">
                    <div class="stat-number">3+</div>
                    <p>سنوات من الخبرة</p>
                </div>
            </div>
        </section>

        <section>
            <h2>المشاريع البارزة</h2>
            <div class="projects">
                <div class="project">
                    <h3>المشروع الأول</h3>
                    <p>وصف مختصر للمشروع الأول وأهميته والتقنيات المستخدمة في تنفيذه.</p>
                </div>
                <div class="project">
                    <h3>المشروع الثاني</h3>
                    <p>وصف مختصر للمشروع الثاني وأهميته والتقنيات المستخدمة في تنفيذه.</p>
                </div>
                <div class="project">
                    <h3>المشروع الثالث</h3>
                    <p>وصف مختصر للمشروع الثالث وأهميته والتقنيات المستخدمة في تنفيذه.</p>
                </div>
            </div>
        </section>

        <section>
            <h2>الأهداف المستقبلية</h2>
            <ul>
                <li>إتقان تطوير تطبيقات Flutter</li>
                <li>تعلم تقنيات جديدة مثل React.js</li>
                <li>المشاركة في مشاريع مفتوحة المصدر</li>
                <li>تطوير مهارات DevOps</li>
            </ul>
        </section>

        <section>
            <h2>تواصل معي</h2>
            <div class="contact-links">
                <a href="#" class="contact-link">🌐 Portfolio</a>
                <a href="#" class="contact-link">💼 LinkedIn</a>
                <a href="#" class="contact-link">📧 Email</a>
                <a href="#" class="contact-link">🐙 GitHub</a>
            </div>
        </section>
    </div>
</body>
</html>
