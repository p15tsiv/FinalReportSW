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
  * Mέθοδος και τεχνικές ανάπτυξης & Αποτελέσματα
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
  * 3) [Bιβλιοθήκη](http://tobiasahlin.com/moving-letters/) για το text animation στην ([ιστοσελίδα participants](https://ioniodi.github.io/D3js-uk-political-donations/participants/))

## Mέθοδος και τεχνικές ανάπτυξης & Αποτελέσματα

#### Παραδοτέο 1 

* Link Παραδοτέου 1 (branch): https://github.com/p15tsiv/D3js-uk-political-donations/tree/Paradoteo1

* Αντικατάσταση της κατάληξης full-viz.html από το URL https://github.com/p15tsiv/D3js-uk-political-donations/full-viz.html με το index.html, έτσι ώστε να εμφανίζεται το URL https://github.com/p15tsiv/D3js-uk-political-donations.

* Τροποποίηση των κωδικών rgba και των HEX, για αλλαγή χρωμάτων στις μπάλες με τα δεδομένα, καθώς και στα αντίστοιχα 3 πεδία της ομαδοποίησης Split by party.

![1](https://user-images.githubusercontent.com/22644519/39819794-07d41d8a-53ad-11e8-86cd-9e6bf3d1c3a4.png)

* Προσθήκη ήχου στα κουμπιά ομαδοποίησης δεδομένων.

* Xρήση της SpeechSynthesisUtterance, έτσι ώστε να ακούγεται το όνομα και το ποσό κάθε δωρητή, "The donor is ... and the amount is ... pounds".

* Χρήση του class = zoom, έτσι ώστε το κείμενο να μεγαλώνει όταν το ποντίκι περνάει από πάνω.

![2](https://user-images.githubusercontent.com/22644519/39820141-c9d05246-53ad-11e8-86c4-8fcf97ef3928.png)

* Προσθήκη νέας ομαδοποίησης δεδομένων, Split by amount, όπου τα ποσά χωρίζονται σε 5 κατηγορίες, a) έως 10,000£, b) έως 50,000£, c) έως 100,000£, d) έως 500,000£ και e) πάνω από 500,000£.

![3](https://user-images.githubusercontent.com/22644519/39820078-a553e478-53ad-11e8-882d-a09ac2d6690f.png)

* Προσθήκη αναζήτησης των στοιχείων του δωρητή στο Google, πατώντας πάνω στην αντίστοιχη μπάλα.

* Δημιουργία αρχείου 2015185.csv.

![4](https://user-images.githubusercontent.com/22644519/39820351-4548fab8-53ae-11e8-8555-3e53f01bf6fa.png)
(screenshot μετά από την παράδοση του β' παραδοτέου)

* Αποστολή 5 φωτογραφιών διαθέσιμων δωρητών, a) The Harrodian School, b) Kerry London, c) CTF Partners, d) Allam Marine, e) Echo Reasearch

#### Παραδοτέο 2 

* Link Παραδοτέου 2 (branch): https://github.com/p15tsiv/D3js-uk-political-donations/tree/Paradoteo2

* Eμφανιση και δυναμική επάκταση της σειράς των εικόνων με τους δωρητές πάνω από τους οποίους πέρασε ο δείκτης του ποντικιού στο γράφημα.

![5](https://user-images.githubusercontent.com/22644519/39820750-383c6674-53af-11e8-86ed-eeae9f874ef6.png)

* Mετατρoπή του αρχείου index.html από το φάκελο participants στη δεσμευμένη μου θέση (Position #021), προσθέτοντας το username μου και το url για το avatar μου και, έπειτα, xρησιμοποιώντας την ήδη υπάρχουσα βιβλιοθήκη και τον open source κώδικα για text animation που βρήκα.

![6](https://user-images.githubusercontent.com/22644519/39821458-f778d17a-53b0-11e8-8c4b-76a28594b8d5.png)

Το αποτέλεσμα φαίνεται στην [ιστοσελίδα](https://ioniodi.github.io/D3js-uk-political-donations/participants/)) των Credits.

#### Βιβλιοθήκες και πηγές κώδικα

* [D3.js](https://d3js.org/).
* [ResponsiveVoice](http://code.responsivevoice.org/responsivevoice.js) (JavaScript) και [API](https://responsivevoice.org/api/) για text-to-speech.
* [Bιβλιοθήκη](https://cdnjs.cloudflare.com/ajax/libs/animejs/2.0.2/anime.min.js) και [κώδικας](http://tobiasahlin.com/moving-letters/#7) για το text animation.
* Κωδικοί για Hex και RBG [κωδικοί χρωμάτων](https://htmlcolorcodes.com/).
* [Zoom on hover CSS](https://www.w3schools.com/howto/howto_css_zoom_hover.asp).
* [.addClass() documentation](https://api.jquery.com/addclass/).
* [Item in array search JavaScript](https://www.w3schools.com/jsref/jsref_indexof_array.asp).
* [Αrray push JavaScript](https://www.w3schools.com/jsref/jsref_push.asp).
