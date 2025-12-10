🌳 Binary Tree Traversal Simulator

Interactive Preorder, Inorder, Postorder & Level-Order (Lineorder) Visualization

Bu proje, ikili ağaç dolaşma yöntemlerini görsel ve adım adım simüle eden etkileşimli bir HTML uygulamasıdır.
Kullanıcı; Preorder, Inorder, Postorder ve Lineorder (Level-Order) algoritmalarının nasıl çalıştığını gerçek zamanlı animasyonlarla izleyebilir.

TailwindCSS ve modern JavaScript teknikleri kullanılarak tasarlanmıştır.

⸻

🚀 Özellikler
	•	✔ 4 farklı traversal yöntemi:
Preorder – Inorder – Postorder – Lineorder (BFS)
	•	✔ Gerçek zamanlı animasyonlu simülasyon
	•	✔ Düğümlerin ziyaret edilme sırasını canlı olarak gösterme
	•	✔ İkili ağacın otomatik çizimi (SVG + HTML)
	•	✔ Responsive tasarım
	•	✔ Node’ların renklerle durumsal vurgulanması:
	•	🟢 current → O anda işlenen düğüm
	•	🔴 visited → Ziyaret tamamlanan düğüm
	•	✔ Gelişmiş UI – TailwindCSS modern tasarım öğeleri
	•	✔ Tek tıklama ile başlatma & sıfırlama mekanizması

⸻

🖥️ Kullanılan Örnek Ağaç

Kod içindeki örnek ikili ağaç yapısı şu şekildedir:

            10
         /      \
       5         15
     /  \      /    \
    2    7   12     20
   /    /         /    \
  1    6        18     25

10 düğümlü dengeli bir ağaçtır ve eğitim amaçlı idealdir.

⸻

🔧 Kullanılan Teknolojiler

Teknoloji	Amaç
HTML5	Arayüz
TailwindCSS	Modern ve responsive UI tasarımı
JavaScript (ES6)	Traversal algoritmaları, animasyon, DOM kontrolü
SVG	Ağaç bağlantılarının çizimi


⸻

📌 Traversal Kuralları

1️⃣ Preorder

Kök → Sol → Sağ
Derinlik öncelikli dolaşma.

2️⃣ Inorder

Sol → Kök → Sağ
Sıralı traversal (BST için artan sıra üretir).

3️⃣ Postorder

Sol → Sağ → Kök
Alt ağaçlar tamamen bittikten sonra kök işlenir.

4️⃣ Lineorder (Level-Order / BFS)

Seviye seviye soldan sağa
Bir kuyruk (Queue) yapısı kullanır.

⸻

▶️ Kurulum & Çalıştırma

Projeyi çalıştırmak için yalnızca HTML dosyasını açmanız yeterlidir.

1. Klonlama

git clone https://github.com/kullanici/tree-traversal-simulator.git
cd tree-traversal-simulator

2. Çalıştırma

Sadece HTML dosyasını çift tıklayın:

index.html

Herhangi bir çerçeve, sunucu veya bağımlılık gerektirmez.

⸻

📸 Ekran Görüntüleri (Opsiyonel)

Aşağıya görüntüler ekleyebilirsiniz:

/screenshots/
    - preorder.png
    - inorder.png
    - postorder.png
    - lineorder.png


⸻

🧠 Kod Yapısı

root
 ├── index.html        → Simülatör (Tüm HTML + JS tek dosyada)
 ├── README.md         → Proje açıklaması
 └── (opsiyonel) screenshots/

Traversal fonksiyonları:
	•	preorderTraversal(node)
	•	inorderTraversal(node)
	•	postorderTraversal(node)
	•	lineorderTraversal(root)
	•	stepTraversal()
	•	renderTree(root)
	•	resetSimulation()

⸻

📚 Öğrenme Amaçlı Harika Bir Araç

Bu uygulama;
	•	Veri Yapıları dersleri
	•	Binary tree temelli algoritma eğitimleri
	•	Traversal mantığını sezgisel açıklamak
	•	Öğrenciler için interaktif sunumlar

gibi pek çok alanda mükemmel bir öğretici araçtır.

⸻

👨‍💻 Geliştirici Notları
	•	Simülasyon hızı SPEED değişkeniyle kontrol edilir.
	•	SVG çizgileri otomatik olarak node koordinatlarına göre hesaplanır.
	•	Düğümler responsive olarak ekran boyutu değiştikçe yeniden hesaplanır.
