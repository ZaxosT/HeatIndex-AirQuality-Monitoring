## HeatIndex and Airquility Monitoring

###### Το πρόβλημα: Mεγάλος βαθμός δυσφορίας και κακής υγιεινής σε σχολικό εργαστηριακό χώρο που φιλοξενεί μεγάλο αριθμό μαθητών και υπολογιστών.

###### Η πρόταση: Μελέτη, σχεδιασμός και ανάπτυξη ενός προτύπου υπολογιστικού συστήματος (physical computing) βασισμένο σε Arduino και Raspberry Pi που θα αλληλεπιδρά με το περιβάλλον κάνοντας συνεχώς μετρήσεις της θερμοκρασίας, της υγρασίας, της ποιότητας του αέρα και της στάθμης έντασης του ήχου μέσα στον εργαστηριακό χώρο.

###### Μέλη της ομάδας:
- Ζαραφίδης Χαράλαμπος: Υπεύθυνος εκπαιδευτικός
- Τσαβδαράς Ζαχαρίας: Προγραμματιστής
- Κιοσκερίδου Χρυσάνθη: Γραφίστρια
- Τσιβελεΐδης Βαλέριος: Μελετητής
- Γρηγοράσκος Γεώργιος: Υπεύθυνος documentation
- Σπυρίδης Ξενοφών: Social Media Manager

###### Χρονοδιάγραμμα
###### Ιανουάριος 2019 - Μάρτιος 2019

###### Ιανουάριος: 
- 1 Εβδομάδα: Μελέτη, ανάπτηξη ιστοσελίδας και παραγγελία υλικών
- 2 & 3 Εβδομάδα: Σχεδιασμός του συστήματος στην πλατοφόρμα tinkercad
- 4 Εβδομάδα: Σχεδιαμός της θήκης του συστήματος

###### Φεβρουάριος:
- 1 & 2 Εβδομάδα: Σχεδιασμός του συστήματος στο υλικό μας
- 3 Εβδομάδα: Δοκιμές και αποσφαλματοποίηση
- 4 Εβδομάδα: Εφαρμογή του υλικού μέσα στην θήκη

###### Μαρτιος:
- 1 Εβδομάδα: Δοκιμή υλικού σε ακραίες θερμοκρασίες και σε ακραία υγρασία
- 2 & 3 Εβδομάδα: Σχεδιασμός και κατασκευή παρουσίασης
- 4 Εβδομάδα: Τελευταίοι έλεγχοι

###### Προγραμματισμός
` Ο προγραμματισμός του συστήματος θα γίνει με το περιβάλλον που παρέχετε για το arduino και με βασικά scripts σε bash για το raspberry. Όσο για την ιστοσελίδα θα γραφτεί σε HTML, CSS, Javascript`  


###### Υλικά:
1. Raspberry Pi 3 Model B ~38.5€
2. Arduino Uno REV 3 ~20€
3. Grove - Temperature & Humidity Sensor Pro ~14.35€
4. Grove - Air quality sensor v1.3 ~9.5€
5. Grove - Dust Sensor ~15.50€
6. LCD Screen ~14.50€


###### Research
###### Πολύ βασικό κομμάτι πάνω στο project μας είναι η μελέτη που θα χρειαστεί ώστε να μπορέσουμε να βγάλουμε ένα αξιόπιστο αποτέλεσμα. Έχουν γίνει πολλές ώρες έρευνας σε αξιόπιστες ιστοσελίδας για το πως παλιό αλλά και καινούριο hardware υπολογιστών προκαλεί μόλυνση στον αέρα.


###### Πώς οι υπολογιστές προκαλούν μόλυνση στον αέρα.

###### Ηλεκτρονικά απόβλητα:
αποστέλλονται στις αναπτυσσόμενες χώρες, οι οποίες τοποθετούνται σε χώρους υγειονομικής ταφής όπου οι άνθρωποι εξάγουν υλικά από αυτά τα ηλεκτρονικά είδη, όπως ο χρυσός, το ασήμι και ο χαλκός. Τα εξαγάγουν με την καύση των ουσιών και αυτή η διαδικασία απελευθερώνει επικίνδυνο καπνό στον αέρα. Τα τοξινά από τον αέρα αγγίζουν επίσης το νερό το οποίο επίσης μολύνεται και προκαλεί κινδύνους για την υγεία. Οι άνθρωποι πίνουν αυτό το νερό και χρησιμοποιούν επίσης για τον καθαρισμό των ρούχων τους.Η χρήση τοξικών υλικών που μπορούν να βλάψουν την υγεία μας μπορεί να προκαλέσει καρκίνο και ο εθισμός στην τεχνολογία μπορεί να οδηγήσει σε άλλα προβλήματα υγείας

###### Εκκαθάριση της γης:
Εννοώντας την "καταστροφή" δασών για την δημιουργία νέων εργοστασίων για την παραγωγοί των ηλεκτρονικών υπολογιστών. Το οποίο αυτό προκαλεί μειώσει στο πόσο τα δέντρα κάνουν φυλοσύνδεση. Με αποτέλεσμα να μην μας παράγουν αρκετό καθαρό οξυγόνο .Σαν αποτέλεσμα να έχουμε περισσότερη μόλυνση αέρος από την μειώσει τον δέντρων.

###### Ενεργειακή σπατάλη:
Οι υπολογιστές συμβάλλουν επίσης στην απώλεια ενέργειας. Τα απόβλητα δημιουργούν περιττή ρύπανση που θα μπορούσε να σωθεί κάθε χρόνο αν οι επιχειρήσεις και τα νοικοκυριά κλείσουν τους υπολογιστές τους και απενεργοποιήσουν τις οθόνες τους όταν δεν τις χρησιμοποιούν.  Το να θέτετε τον υπολογιστή σας σε κατάσταση αναμονής ή αφήνοντας την οθόνη σας σε κατάσταση αναστολής δημιουργεί επίσης σπατάλη ενέργειας, καθώς αυτές οι λειτουργίες εξακολουθούν να απαιτούν ενέργεια. Ακόμα και οταν δεν χρησιμοποιηται τον υπολογιστή σας, ενώ είναι απενεργοποιημένος, θα τραβήξει μια μικρή ποσότητα ενέργειας από την πρίζα. Αυτή η ενεργειακή σπαταλη μεταφράζεται σε αέρια που υπερβαίνουν το φαινόμενο του θερμοκηπίου και συμβάλλουν στη ρύπανση και την κλιματική αλλαγή.

###### Παραγωγή:
Η παραγωγή ηλεκτρονικών υπολογιστών δημιουργεί ρύπανση. Η κατασκευή υπολογιστών απαιτεί μεγάλη ποσότητα ορυκτών καυσίμων και χημικών ουσιών. Παρά το γεγονός ότι οι υπολογιστές συνεχίζουν να μειώνονται σε μέγεθος, οι υπολογιστές εξακολουθούν να απαιτούν 10 φορές το βάρος τους σε χημικές ουσίες και ρύπους κατά τη διάρκεια της κατασκευής. Η ρύπανση που προκαλείται από την παραγωγή ηλεκτρονικών υπολογιστών είναι επιβλαβής για την υγεία όσων ζουν σε άμεση γειτνίαση με τις εγκαταστάσεις παραγωγής που εκλύουν επιβλαβείς χημικές ουσίες και ρύπους στον αέρα.

