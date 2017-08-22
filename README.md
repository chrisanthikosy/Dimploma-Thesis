# Dimploma-Thesis


# Τίτλος Πτυχιακής : Μελέτη Ανάπτυξης ανίχνευσης συναισθημάτων με έμφαση στα κοινωνικά δίκτυα

Σκοπός της παρούσας εργασίας: Σκοπός της εργασίας είναι η ανίχνευση συναισθημάτων στα κοινωνικά δίκτυα μέσω του περιεχομένου που οι ίδιοι οι χρήστες καθημερινά ανεβάζουν στα κοινωνικά δίκτυα. Για τις ανάγκες της συγκεκριμένης εργασίας θα χρησιμοποιήσουμε την πλατφόρμα μικροιστολόγησης, το Twitter.

Το Twitter αποτελεί ένα από τα δημοφιλέστερα κοινωνικά δίκτυα εν έτη 2017. Συγκεκριμένα δίνει την δυνατότητα στους χρήστες να δημοσιεύσουν σύντομα μηνύματα(μέχρι 140 χαρακτήρες) με σκοπό να εκφράσουν την αποψή τους πάνω σε διάφορα θέματα όπως πολιτική, θέματα που βρίσκονται την εν λόγω χρονική στιγμή στην επικαιρότητα, αθλητισμός, θεατρικά δρώμενα κ.α. Καθημερινά δημοσιεύονται πάνω από 300,000,000 tweets σε καθημερινή βάση ενώ αριθμεί πάνω από 350 εκατομμύρια χρήστες (πηγή: http://www.internetlivestats.com/). 

Οι χρήστες έχοντας την ανάγκη να εκφράσουν την αποψή τους πάνω σε διάφορα γεγονότα και διάφορες καταστάσεις που εξελίσσονται καθημερινά βρίσκουν στρέφουν την προσοχή τους προς τα κοινωνικά δίκτυα είτε για να πουν και αυτή την αποψή τους και να βρουν ουσιαστικά κάποιους που μπορούν να τους κατανοήσουν είτε να παρακολουθήσουν την επικαιροτητα μέσω από τα κοινωνικά δίκτυα. Προκειμένου να υπάρχει αλληλεπίδραση μεταξύ των χρηστών και να έχουν πρόσβαση σε posts που αναρτούνται καθημερινά, δημιουργούν ένα δίκτυο ακολουθώντας άλλους χρήστες. Ωστόσο ακολουθώντας άλλους χρήστες μπορεί να ερμηνευθεί ως ένδειξη εμπιστοσύνης στα λεγόμενα των χρηστών που επιλέγουμε να ακολουθήσουμε. Ως επί των πλείστον παρατηρείται η εξής παραδοχή: Αν κάποιος χρήστης έχει πολλούς followers και αυτά που αποφασίζει να αναρτήσει έχουν μέγαλη δημοτικότητα προς το ευρύ κοινό, τότε συνεπάγεται ότι ο εν λόγω χρήστης θεωρείται δημοφιλής. Άρα το συμπέρασμα το οποίο προκύπτει, δεχόμενοι την παραπάνω παραδοχή, είναι ότι ο αριθμός των followers θεωρείται μέτρο δημοτικότητας. Επιπλέον βασιζόμενοι σε αυτό το συμπέρασμα γίνεται επίσης κατανοητό ότι οι δημοφιλείς λογαριασμοί χρηστών εμφανίζονται στους άλλους χρήστες ως "προτεινόμενοι". Συνεπώς με αυτό τον τρόπο επεκτείνεται πιο γρήγορα το δίκτυο.


Ρίχνοτας μια πρόχειρη ματιά στο Twitter, γίνεται αμέσως αντιληπτό ότι τα θέματα τα οποία διεγείρουν περισσότερο το ενδιαφέρον των χρηστών είναι θέματα σχετικά με την πολιτική και θέματα που σχείζονται κυρίως με εκπομπές της τηλεόρασεις. Προκειμένου να έχουν οι χρήστες την δυνατότητα να συμμετέχουν σε ένα κοινό θέμα συζήτησεις, έχουμε την δημιουργία των hashtags. Τα hashtags αποτελούν λέξεις-κλειδιά γύρω από ένα θέμα και κάνοντας χρήση αυτών υπάρχει η δυνατότητα ενός "διαδικτυακού διαλόγου" χωρίς ουσιαστικά να υπάρχει αλληλεπίδραση μεταξύ των χρηστών. Συμβολίζονται με # πριν την λέξη κλείδι που θέλουμε να προσθέσουμε.

Επιστρέφοντας στα θέματα στα οποία οι χρήστες συνήθως προτιμούν τα ασχοληθούν, ας σταθούμε σε θέματα πολιτικής. Λαμβάνοτας υπόψιν ότι το Twitter είναι ένα κοινωνικό δίκτυο, ευρείας χρήσης και με εκατομμυρία χρήστες καταλήγουμε στο γεγονός ότι πολλά πολιτικά ζητήματα που εξελίσσονται σε διαφορετικές χώρες και ηπείρους(π.χ Αμερική) δεν θα μπορούσαν να αφήσουν και εμάς ανεπηρέαστους(π.χ Ελλάδα). Αναμφίβολα δυο από τα σημαντικότερα γεγονότα που έγιναν το 2016 ήταν το Brexit και οι εκλογές της 8ης Νοεμβρίου στην Αμερική. Στην πρώτη περίπτωση οι κάτοικοι του Ηνωμένου Βασιλείου καλούνταν σε δημοψήφισμα σχετικά με το αν η Βρετανία θα παραμείνει ή όχι στην Ευρωπαική Ένωση. Στην δεύτερη πεπίπτωση οι κάτοικοι της Αμερικής ήταν υποχρεωμένοι να εκλέξουν τον επόμενο πρόεδρο τους μεταξύ του Donald Trump( υποψήφιος με το κόμμα των Ρεπουμπλικανών) και την Hilary Clinton (υποψήφια με το κόμμα των Δημοκρατικών). Κάτα την διάρκεια της προεκλογικής εκστρατείας των δυο υποψηφίων σίγουρα ήταν ένα θέμα που μονοπώλησε το ενδιαφέρον των πολιτών. Επίσης αποτέλεσε και ένα από τα πρώτα θέματα συζήτησης στα κοινωνικά δίκτυα. 


Σκόπος της εργασίας είναι βάση των σχολιασμών που έγιναν από χρήστες στο Twitter να γίνει εξαγωγή των δεδομένων αυτών προκειμένου να γίνει κατηγοροποιήση των συναισθημάτων των χρηστών, βασιζόμενοι σε αυτά τα δεδομένα. Ωστόσο θα γίνει προσπάθεια εντοπισμού ειρωνείας σε αυτά. Η ειρωνεία είναι ένα συχνό φαινόμενο στα κοινωνικά δίκτυα. Θα γίνει προσπάθεια εντοπισμού σε αυτά που αναρτούν οι χρήστες και να ενταχθεί σε ξεχωριστή κατηγορία.
