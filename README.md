# Veri Yapıları Ödevi: Arama ve Sıralama Algoritmaları

Bu proje, temel arama ve sıralama algoritmalarının Python uygulamalarını ve bu algoritmaların performans analizlerini içerir.

## 📊 Algoritma Analizi ve Big-O Karmaşıklığı

| Algoritma | Ortalama Karmaşıklık | En Kötü Durum | Tür |
| :--- | :--- | :--- | :--- |
| **Linear Search** | $O(n)$ | $O(n)$ | Arama |
| **Binary Search** | $O(\log n)$ | $O(\log n)$ | Arama |
| **Bubble Sort** | $O(n^2)$ | $O(n^2)$ | Sıralama |
| **Selection Sort** | $O(n^2)$ | $O(n^2)$ | Sıralama |
| **Merge Sort** | $O(n \log n)$ | $O(n \log n)$ | Sıralama |
| **Quick Sort** | $O(n \log n)$ | $O(n^2)$ | Sıralama |

## 💡 Algoritmaların Çalışma Mantığı

### Arama Algoritmaları:
1. **Linear Search:** Listenin başından başlar ve hedef elemanı bulana kadar her öğeyi tek tek kontrol eder.
2. **Binary Search:** Sadece sıralı listelerde çalışır. Listeyi sürekli ikiye bölerek hedef elemanın hangi yarıda olduğunu kontrol eder.

### Sıralama Algoritmaları:
1. **Bubble Sort:** Yan yana olan elemanları kıyaslar ve büyük olanı sağa kaydırarak ilerler.
2. **Selection Sort:** Listenin içindeki en küçük elemanı bulur ve listenin başına taşır.
3. **Merge Sort:** Listeyi tek eleman kalana kadar böler, sonra bu parçaları sıralı bir şekilde birleştirir.
4. **Quick Sort:** Bir pivot eleman seçer; pivotun soluna küçükleri, sağına büyükleri toplar.

## 🛠️ Nasıl Çalıştırılır?
* Proje bir Jupyter Notebook (`.ipynb`) dosyasıdır.
* **Google Colab**, **VS Code** veya **Jupyter** üzerinden açarak tüm hücreleri çalıştırabilirsiniz.

