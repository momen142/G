<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقع الدكتور [اسم الطبيب]</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            float: right;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 2rem;
        }
        .section {
            margin-bottom: 2rem;
            padding: 1rem;
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }
        .services {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }
        .service {
            flex: 1 1 300px;
            padding: 1rem;
            background-color: #f9f9f9;
            border-radius: 5px;
        }
        .contact-info {
            margin-top: 1rem;
        }
        .tips {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 1rem;
        }
        .tip {
            padding: 1rem;
            background-color: #e8f5e9;
            border-radius: 5px;
        }
        .booking-form {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 1rem;
        }
        @media (max-width: 768px) {
            .booking-form {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>مرحباً بكم في عيادة الدكتور [اسم الطبيب]</h1>
        <p>نقدم لكم أفضل الخدمات الطبية والرعاية الصحية</p>
    </header>

    <nav>
        <a href="#tips">النصائح الطبية</a>
        <a href="#online">استشارة أونلاين</a>
        <a href="#booking">حجز استشارة</a>
        <a href="#contact">اتصل بنا</a>
        <a href="#services">الخدمات</a>
        <a href="#about">من نحن</a>
        <a href="#home">الرئيسية</a>
    </nav>

    <div class="container">
        <section id="home" class="section">
            <h2>مرحباً بكم</h2>
            <p>نرحب بكم في الموقع الرسمي لعيادة الدكتور [اسم الطبيب]. نحن نقدم خدمات طبية عالية الجودة لضمان راحتكم وصحتكم.</p>
            <img src="https://via.placeholder.com/800x400?text=عيادة+الطبيب" alt="صورة العيادة" style="width:100%; max-width:800px; height:auto; margin-top:1rem;">
        </section>

        <section id="about" class="section">
            <h2>من نحن</h2>
            <p>الدكتور [اسم الطبيب] هو استشاري في [التخصص الطبي] مع أكثر من [عدد] سنوات من الخبرة في مجال الطب. تخرج من [اسم الجامعة] وحاصل على شهادة البورد في [التخصص].</p>
            <p>نسعى في عيادتنا لتقديم أفضل رعاية طبية ممكنة باستخدام أحدث التقنيات والأساليب الطبية.</p>
        </section>

        <section id="services" class="section">
            <h2>الخدمات الطبية</h2>
            <div class="services">
                <div class="service">
                    <h3>الخدمة الأولى</h3>
                    <p>وصف مختصر للخدمة الأولى التي يقدمها الطبيب.</p>
                </div>
                <div class="service">
                    <h3>الخدمة الثانية</h3>
                    <p>وصف مختصر للخدمة الثانية التي يقدمها الطبيب.</p>
                </div>
                <div class="service">
                    <h3>الخدمة الثالثة</h3>
                    <p>وصف مختصر للخدمة الثالثة التي يقدمها الطبيب.</p>
                </div>
            </div>
        </section>

        <section id="booking" class="section">
            <h2>حجز استشارة</h2>
            <form class="booking-form">
                <div>
                    <label for="bname">الاسم الكامل:</label>
                    <input type="text" id="bname" name="bname" required style="width:100%; padding:8px; margin-bottom:1rem;">
                </div>
                <div>
                    <label for="bphone">رقم الهاتف:</label>
                    <input type="tel" id="bphone" name="bphone" required style="width:100%; padding:8px; margin-bottom:1rem;">
                </div>
                <div>
                    <label for="bemail">البريد الإلكتروني:</label>
                    <input type="email" id="bemail" name="bemail" style="width:100%; padding:8px; margin-bottom:1rem;">
                </div>
                <div>
                    <label for="bdate">التاريخ المفضل:</label>
                    <input type="date" id="bdate" name="bdate" required style="width:100%; padding:8px; margin-bottom:1rem;">
                </div>
                <div>
                    <label for="btime">الوقت المفضل:</label>
                    <select id="btime" name="btime" required style="width:100%; padding:8px; margin-bottom:1rem;">
                        <option value="">اختر الوقت</option>
                        <option value="9-12">9 صباحاً - 12 ظهراً</option>
                        <option value="12-3">12 ظهراً - 3 عصراً</option>
                        <option value="3-6">3 عصراً - 6 مساءً</option>
                    </select>
                </div>
                <div>
                    <label for="breason">سبب الاستشارة:</label>
                    <textarea id="breason" name="breason" rows="3" required style="width:100%; padding:8px; margin-bottom:1rem;"></textarea>
                </div>
                <div style="grid-column: span 2;">
                    <button type="submit" style="background-color:#4CAF50; color:white; padding:10px 20px; border:none; cursor:pointer; width:100%;">تأكيد الحجز</button>
                </div>
            </form>
        </section>

        <section id="online" class="section">
            <h2>استشارة عبر الإنترنت</h2>
            <p>يمكنكم الآن حجز استشارة طبية عبر الإنترنت مع الدكتور [اسم الطبيب] من خلال الفيديو أو المحادثة النصية.</p>
            
            <div style="background-color:#e3f2fd; padding:1rem; border-radius:5px; margin:1rem 0;">
                <h3>كيف تعمل الاستشارة عبر الإنترنت؟</h3>
                <ol>
                    <li>اختر نوع الاستشارة (فيديو/محادثة)</li>
                    <li>حدد التاريخ والوقت المناسبين</li>
                    <li>ادفع رسوم الاستشارة</li>
                    <li>ستتلقى رابط الجلسة على بريدك الإلكتروني</li>
                </ol>
            </div>

            <form>
                <div style="margin-bottom:1rem;">
                    <label>نوع الاستشارة:</label><br>
                    <input type="radio" id="video" name="consultType" value="video" checked>
                    <label for="video">فيديو</label>
                    <input type="radio" id="chat" name="consultType" value="chat">
                    <label for="chat">محادثة نصية</label>
                </div>
                <div style="display:grid; grid-template-columns:1fr 1fr; gap:1rem; margin-bottom:1rem;">
                    <div>
                        <label for="ondate">التاريخ:</label>
                        <input type="date" id="ondate" name="ondate" required style="width:100%; padding:8px;">
                    </div>
                    <div>
                        <label for="ontime">الوقت:</label>
                        <input type="time" id="ontime" name="ontime" required style="width:100%; padding:8px;">
                    </div>
                </div>
                <button type="submit" style="background-color:#2196F3; color:white; padding:10px 20px; border:none; cursor:pointer;">حجز الاستشارة (رسوم: 100 ريال)</button>
            </form>
        </section>

        <section id="tips" class="section">
            <h2>النصائح الطبية</h2>
            <div class="tips">
                <div class="tip">
                    <h3>نصيحة للوقاية من الأمراض</h3>
                    <p>احرص على غسل اليدين بانتظام، خاصة قبل الأكل وبعد استخدام الحمام.</p>
                </div>
                <div class="tip">
                    <h3>نصيحة غذائية</h3>
                    <p>تناول 5 حصص من الخضار والفواكه يومياً لتعزيز مناعتك.</p>
                </div>
                <div class="tip">
                    <h3>نصيحة للصحة النفسية</h3>
                    <p>خصص 30 دقيقة يومياً لممارسة الرياضة أو التأمل لتحسين صحتك النفسية.</p>
                </div>
                <div class="tip">
                    <h3>نصيحة للنوم الصحي</h3>
                    <p>احرص على النوم 7-8 ساعات يومياً في غرفة مظلمة وهادئة.</p>
                </div>
            </div>
        </section>

        <section id="contact" class="section">
            <h2>اتصل بنا</h2>
            <div class="contact-info">
                <p><strong>العنوان:</strong> [عنوان العيادة]</p>
                <p><strong>الهاتف:</strong> [رقم الهاتف]</p>
                <p><strong>البريد الإلكتروني:</strong> [البريد الإلكتروني]</p>
                <p><strong>ساعات العمل:</strong> [أوقات العمل]</p>
            </div>
            <form>
                <h3>أرسل رسالة</h3>
                <div style="margin-bottom:1rem;">
                    <label for="name">الاسم:</label>
                    <input type="text" id="name" name="name" style="width:100%; padding:8px;">
                </div>
                <div style="margin-bottom:1rem;">
                    <label for="email">البريد الإلكتروني:</label>
                    <input type="email" id="email" name="email" style="width:100%; padding:8px;">
                </div>
                <div style="margin-bottom:1rem;">
                    <label for="message">الرسالة:</label>
                    <textarea id="message" name="message" rows="5" style="width:100%; padding:8px;"></textarea>
                </div>
                <button type="submit" style="background-color:#4CAF50; color:white; padding:10px 20px; border:none; cursor:pointer;">إرسال</button>
            </form>
        </section>
    </div>

    <footer>
        <p>© 2023 عيادة الدكتور [اسم الطبيب]. جميع الحقوق محفوظة.</p>
    </footer>
</body>
</html>
