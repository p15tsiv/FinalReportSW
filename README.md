# Τεχνολογία Λογισμικού
## Οπτικοποίηση δεδομένων χορηγιών (UK)

#### Στοιχεία φοιτητή
##### Ονοματεπώνυμο: Τσιβιντζέλη Χρύσα
##### Αριθμός Μητρώου: Π2015185
##### Εξάμηνο φοίτησης: ΣΤ'
##### github username: p15tsiv
##### email: p15tsiv@ionio.gr

#### Σύνδεσμοι
##### Link ιστοσελίδας της εφαρμογής μου: [Link εκτελέσιμου](https://p15tsiv.github.io/D3js-uk-political-donations/)

##### Αποθετήριο του κώδικα της εφαρμογής (master branch) \: [Link αποθετηρίου κώδικα](https://github.com/p15tsiv/D3js-uk-political-donations)

##### Link στο κλαδί του κώδικα που αντιστοιχεί στο Παραδοτέο 1(Paradoteo-1 branch) \: [Link branch κώδικα Παραδοτέο 1](https://github.com/p15tsiv/D3js-uk-political-donations/tree/Paradoteo1)

##### Link στο κλαδί του κώδικα που αντιστοιχεί στο Παραδοτέο 2(Paradoteo-2 branch) \: [Link branch κώδικα Παραδοτέο 2](https://github.com/p15tsiv/D3js-uk-political-donations/tree/Paradoteo2)

##### Link ιστοσελίδας της Τελικής Αναφοράς μου: [Link github-page Final Report](https://p15tsiv.github.io/FinalReportSW/)

##### Αποθετήριο της Τελικής Αναφοράς μου: [Link repository Final Report](https://github.com/p15tsiv/FinalReportSW)

### Πίνακας Περιεχομένων
  * Σύνοψη
  * Εισαγωγή
  * Aνάλυση σχετικών έργων και εργαλείων
  * Mέθοδος και τεχνικές ανάπτυξης
  * Aποτελέσματα
    * Παραδοτέο 1
    * Παραδοτέο 2
  * Συμπεράσματα
  * Bιβλιογραφία και σύνδεσμοι σε σχετικές εργασίες
    * Βιβλιοθήκες και πηγές κώδικα

## Σύνοψη

Για την υλοποίηση της εργασίας, πρέπει να χρησιμοποιηθούν τα εξής: η βιβλιοθήκη D3 της JavaScript και οι σελίδες github pages έτσι ώστε να προσαρμοστεί η ιστοσελίδα σε ανάγκες χρηστών με προβλήματα όρασης, αξιοποιώντας τις δυνατότητες της γλώσσας JavaScript για λειτουργίες μεγέθυνσης κειμένου και text-to-speech.

Ως βάση για την εργασία δίνεται το εξής [αποθετήριο του github](https://github.com/ioniodi/D3js-uk-political-donations), από το οποίο οπτικοποιούνται οι δωρεές σε πολιτικά κόμματα της Μεγάλης Βρετανίας.

## Εισαγωγή

Η [εφαρμογή](https://p15tsiv.github.io/D3js-uk-political-donations/) χρησιμοποιεί τη βιβλιοθήκη D3 της JavaScript για οπτικοποίηση των δεδομένων των χορηγιών προς πολιτικά κόμματα της Μεγάλης Βρετανίας. 

Ο χρήστης μπορεί να πλοηγηθεί ανάμεσα σε διάφορες μορφές αναπαράστασης των δεδομένων ώστε να του παρέχονται περισσότερες πληροφορίες, ανάλογα με το κουμπί που θα επιλέξει (All money, The public's purse, Split by party, Split by type of donor, Split by amount). Η εφαρμογή συνδέεται με το Google Search με ένα κλικ σε μπάλα του γραφήματος για πρόσβαση σε περισσότερα στοιχεία για τον εκάστοτε δωρητή. Για περισσότερες πληροφορίες των δωρητών, εμφανίζεται ένα παράθυρο κάνοντας hover πάνω από κάποια μπάλα του γραφήματος και μια σειρά των εικόνων των δωρητών που έχει ήδη "επισκεφτεί" για περισσότερη ευκολία. Με την πρόσθεση εργαλείων όπως η μεγέθυνση κειμένου με hover πάνω από το κείμενο και η λειτουργία text-to-speech, η εφαρμογή προσαρμόζεται στις ανάγκες των χρηστών-αναγνωστών με προβλήματα όρασης.

## Aνάλυση σχετικών έργων και εργαλείων

* Τροποποίησα το [αποθετήριο του github](https://github.com/ioniodi/D3js-uk-political-donations) αφού το έκανα fork για να προσθέσω τα ζητούμενα των παραδοτέων της εξαμηνιαίας εργασίας.

* Χρησιμοποίησα το σύστημα Github Pages, για επεξεργασία των παρακάτω: ("[index.html](https://github.com/p15tsiv/D3js-uk-political-donations/blob/gh-pages/index.html)",
"[chart.js](https://github.com/p15tsiv/D3js-uk-political-donations/blob/gh-pages/chart.js)"
και "[style.css](https://github.com/p15tsiv/D3js-uk-political-donations/blob/gh-pages/style.css)").

* Από έτοιμες βιβλιοθήκες, χρησιμοποίησα τις εξής:
  * 1) D3 της JavaScript.
  * 2) [ResponsiveVoice](http://code.responsivevoice.org/responsivevoice.js) (JavaScript) για text-to-speech.
  * 3) [Bιβλιοθήκη](http://tobiasahlin.com/moving-letters/) για το text animation (Βλ. [ιστοσελίδα participants](https://ioniodi.github.io/D3js-uk-political-donations/participants/))
