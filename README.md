 Pathfinding Simülasyonu (C++)

Bu proje, **C++ konsol tabanlı** bir **pathfinding (yol bulma)** simülasyonudur.  
2D bir grid üzerinde başlangıç (S) ve hedef (E) noktaları belirlenir, engeller (X) yerleştirilir ve en kısa yol **A*** veya **Dijkstra** algoritması ile hesaplanır.  

---

##  Özellikler
- 20x20 grid üzerinde yol bulma
- Başlangıç noktası: (0,0) → `S`
- Hedef noktası: (19,19) → `E`
- Engel ekleme (`X`)
- **A\*** veya **Dijkstra** seçme
- En kısa yol bulunduğunda `*` ile işaretlenir
- ASCII grid çıktısı

---
=== PATHFINDING SIMULASYONU ===
Algoritma sec: (1) A* (2) Dijkstra : 1
Engel sayisini gir: 5
Engel 1 (x y): 2 2
Engel 2 (x y): 3 2
Engel 3 (x y): 4 2
Engel 4 (x y): 5 2
Engel 5 (x y): 6 2


**Başlangıç grid:**


S . . . . . . . . . . . . . . . . . .
. . . . . . . . . . . . . . . . . . .
. . X . . . . . . . . . . . . . . . .
. . X . . . . . . . . . . . . . . . .
. . X . . . . . . . . . . . . . . . .
. . X . . . . . . . . . . . . . . . .
. . X . . . . . . . . . . . . . . . .
. . . . . . . . . . . . . . . . . . .
. . . . . . . . . . . . . . . . . . .
. . . . . . . . . . . . . . . . . . E


**Yol bulundu:**


S * * * * * * * * * * * * * * * * * *
. . . . . . . . . . . . . . . . . . *
. . X . . . . . . . . . . . . . . . *
. . X . . . . . . . . . . . . . . . *
. . X . . . . . . . . . . . . . . . *
. . X . . . . . . . . . . . . . . . *
. . X . . . . . . . . . . . . . . . *
. . . . . . . . . . . . . . . . . . *
. . . . . . . . . . . . . . . . . . *
. . . . . . . . . . . . . . . . . . E


---

## ⚙ Çalıştırma
1. Kodu `pathfinding.cpp` dosyasına kaydedin.
2. Terminalde derleyin:
   ```bash
   g++ pathfinding.cpp -o pathfinding


Çalıştırın:

./pathfinding

Not:Çalıştırma örneğini yapmakta baya bi zorlandım eğer anlaşılmazsa özür dilerim

