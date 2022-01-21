# GTU---CSE-101---Term-Project---Counter-Crowded-
Gebze Technical University CSE 101 Term Project. (Group 20)

Project Name: Counter-Crowded

Purpose: Prevent the overcrowded places. During Covid-19 limited seats are example for project's usage area and how necessary this project is.

Counter Crowded detects with 2 HC-SR04 sensor whether someone enters or exits. According to acitons there are some steps to take.

1- If somenone is entering, entry led will turn on yellow and exit led will turn on red. In this way, people can understand somebodys is entering and we can prevent collisions. Same process takes place as vice versa when someone exits. If both of the leds are green, this means people are free to enter or exit. 

LCD screen displays;

When there is no action ---------------------- the Quota,

While entering ------------------------------------- "Entering...",

While leaving --------------------------------------- "Leaving...",

When it reached to its full capacity ----- "Full Capacity".


2- When we watch the video, the quota is arranged for 4 people. After the room has reached its full capacity buzzer will sound and both of the leds will turn on red. So, people in the queue and inside can understand the room is full.

3- If someone try to enter after full capacity the buzzer will sound. So, we will prevent overcrowded rooms.

Equipments:

1 x Arduino UNO

1 x LCD ekran with I2C

2 x HC-SR04 Sensor

2 x Breadboard

1 x 9V battery and its connections

2 x RGB Leds

1 x Buzzer

4 x 330 Ω Resistors

Jumper Cables

---------------------------------------------------------------------------------------------------------------------------

Gebze Teknik Üniversitesi CSE 101 dönem projesi. (Grup 20)

Proje Adı: Counter-Crowded

Amacı: Bir oda, salon vb. için belirlenen kişi sayısından fazlasının alınmasını önlemek. Özellikle Covid-19 döneminde hayatımıza yerleşen bazı yerlerde sınırlı sayıda kişi alımı yapılması kullanım alanına ve gerekliliğine örnek olarak verilebilir.

Counter Crowded kapalı bir alana giren veya çıkan kişiyi Kapıya yerleştirilen 2 adet HC-SR04 sensörü sayesinde algılayıp giriş veya çıkış yapılması durumuna göre işlemler gerçekleştirmektedir.

1- Eğer giriş yapılıyorsa giriş ledi sarı yanmakta çıkış ledi kırmızı yanmaktadır. Böylece giriş tarafında bir işlem yapıldığı çıkış tarafına bildirilir ve yaşanabilecek çakışmalara karşı kullanıcılar uyarılır. Aynı durum çıkış yapılırken de tam tersi şeklinde gerçekleşir. 
İki led de yeşil yandığında iki tarafın da işlem için uygun olduğunu göstermektedir.

LCD ekranda,

Sistemde hareket yokken içerideki kişi sayısı,

Giriş yapılırken giriş yapılıyor,

Çıkış yapılırken çıkış yapılıyor ,

Maksimum kapasitede tam kapasite yazmaktadır.


2- Videoyu ele aldığımızda 4 kişilik kapasiteye sahip bir kapalı alan da 4. kişi girdikten sonra zil öter ve iki led de kırmızı yanar. Böylece o kişinin girmesiyle odanın maksimum kapasiteye ulaştığı hem girmek için bekleyen kişilere hem de içerideki kişilere bildirilmiş olur.

3- Maksimum kapasiteden sonra girmeye çalışan olursa zil ötecek. Bu sayede fazla kişilerin girmesi önlenmiş olacak.

Gerekli ekipmanlar:

1 x Arduino UNO

1 x LCD ekran (I2C ile beraber)

2 x HC-SR04 Sensör

2 x Breadboard

1 x 9V pil ve bağlantıları

2 x RGB Led

1 x Buzzer

4 x 330 Ω Direnç

Jumper Kablolar
