 Day 10 – K-Nearest Neighbors (KNN) Classifier (Iris Dataset)

 Περιγραφή
Σε αυτό το project εφαρμόζουμε τον K-Nearest Neighbors (KNN) αλγόριθμο στο Iris dataset.  
Το KNN είναι ένα non-parametric μοντέλο που προβλέπει την κλάση ενός δείγματος με βάση τους κοντινότερους "γειτόνους" του στο χώρο των χαρακτηριστικών.

---

 Βήματα
1. Φόρτωση του Iris dataset από το Seaborn.  
2. Κανονικοποίηση των χαρακτηριστικών με StandardScaler.  
3. Εκπαίδευση KNN Classifier με k=5.  
4. Αξιολόγηση του μοντέλου με accuracy και classification report.  
5. Οπτικοποίηση Confusion Matrix.  
6. Μελέτη της ακρίβειας για διαφορετικές τιμές του k (1–20).

---

 Αποτελέσματα
- Accuracy ~96–100% (ανάλογα με το split).  
- Το KNN αποδίδει εξαιρετικά στο Iris dataset, αφού τα classes είναι καθαρά διαχωρίσιμα.  
- Παρατηρείται ότι το πολύ μικρό K (π.χ. K=1) κάνει overfitting, ενώ πολύ μεγάλο K (π.χ. K>10) μειώνει την ακρίβεια.  

---

 Τι έμαθα
- Πώς λειτουργεί ο αλγόριθμος K-Nearest Neighbors:  
  βασίζεται στην απόσταση (distance) μεταξύ δειγμάτων.  
- Η σημασία του scaling (Standardization) σε distance-based μοντέλα.  
- Πώς να επιλέγω το βέλτιστο K με δοκιμές και οπτικοποίηση.  
- Πώς να χρησιμοποιώ loops για testing διαφορετικών υπερπαραμέτρων (hyperparameters).  
