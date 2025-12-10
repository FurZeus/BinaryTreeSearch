İkili Ağaç Dolaşma Simülatörü

Bu proje, temel veri yapılarından biri olan İkili Ağaç (Binary Tree) üzerindeki dört farklı dolaşma (traversal) yöntemini görsel olarak simüle eden tek dosyalık, etkileşimli bir HTML uygulamasıdır. Tailwind CSS kullanılarak modern ve duyarlı bir tasarımla geliştirilmiştir.

🌟 Özellikler

Dört Dolaşma Yöntemi:

Preorder (Kök → Sol → Sağ)

Inorder (Sol → Kök → Sağ)

Postorder (Sol → Sağ → Kök)

Lineorder (BFS): Seviye Seviye (Kuyruk tabanlı)

Görselleştirme: Ağaç yapısı, düğümler ve bağlantılarla net bir şekilde gösterilir.

Adım Adım Animasyon: Her dolaşma yönteminin adımları 1 saniyelik gecikmeyle (1000ms) düğümlerin rengi değiştirilerek gösterilir.

Gerçek Zamanlı Sonuç: Ziyaret edilen düğümler anlık olarak sonuç alanına eklenir.

🛠️ Nasıl Çalışır?

Proje, tamamen istemci taraflı (client-side) HTML, CSS (Tailwind) ve saf JavaScript kullanılarak geliştirilmiştir. Harici bir bağımlılığa veya sunucuya ihtiyaç duymaz.

Ağaç Yapısı

Simülasyonda kullanılan örnek ikili ağaç, aşağıdaki sayısal değerlere ve yapıya sahiptir:

        10
     /      \
    5        15
   / \      /  \
  2   7    12  20
 /   /         / \
1   6        18  25


Beklenen Dolaşma Sonuçları

Simülasyonu başlattığınızda alacağınız sıralar (ziyaret sırası) şunlardır:

Yöntem

Kural

Sonuç Sırası

Preorder

Kök-Sol-Sağ

10 5 2 1 7 6 15 12 20 18 25

Inorder

Sol-Kök-Sağ

1 2 5 6 7 10 12 15 18 20 25

Postorder

Sol-Sağ-Kök

1 2 6 7 5 12 18 25 20 15 10

Lineorder

Seviye Seviye (BFS)

10 5 15 2 7 12 20 1 6 18 25

🚀 Başlangıç

Bu projeyi yerel olarak çalıştırmak veya GitHub Pages ile yayınlamak için:

Bu depoyu klonlayın veya zip dosyasını indirin.

tree_traversal_simulator.html dosyasını favori tarayıcınızla (Chrome, Firefox vb.) açın.

İstediğiniz dolaşma yöntemine tıklayarak simülasyonu başlatın.
