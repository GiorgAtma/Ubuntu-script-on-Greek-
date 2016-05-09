# unixgadged 
 
 > Author       : Atmatsidis Giwrgos <https://github.com/GiwrgosAtmatsidis>                                        

 > Released On  : Friday 04 September 2015
 
 > Version      : 1.0.1  current version doesn't have a graphic environment. The navigation is from terminal

               Αυτό το script σας επιτρέπει πολύ εύκολα να κάνετε τις παρακάτω ενέργειες:

          1. Eνημέρωση - Aναβάθμιση
          2. Θέλω τον καθαρισμό του συστήματος και τους παλαιούς πυρήνες
          3. Έχω πρόβλημα στο Τερματικό καθώς εκτελώ 'apt-get update' && 'apt-get upgrade
          4. Θέλω να δω τις αναλυτικές πληροφορίες του συστήματος μου
          5. Θέλω να δω ποιό είναι το μοντέλο της κάρτας γραφικών και ποιόν οδηγό (driver) χρησιμοποιεί
          6. Θέλω να δω πληροφορίες για την κάρτα του δικτύου και,τον οδηγό(driver) ο οποίος χρησιμοποιείται
          7. Θέλω να δω πόσα GB έχει γράψει ο δίσκος (Χρήσιμο για σκληρούς δίσκους (πχ SSD)
          8. Θέλω να δω τον αριθμό των πακέτων καθώς επίσης και των βιβλιοθηκών - εξαρτήσεων του συστήματος που είναι εγκατεστημένα
          9. Θέλω να δω τις πληροφορίες του επεξεργαστή CPU     
          10. Θέλω να δω τις πληροφορίες της μνήμης RAM και προβολή του μεγέθους της μνήμης σε gigabyte και την προβολή Swap που είναι σε χρήση
          11. Θέλω να δω τα διαμερίσματα που έχω στον δίσκο μου για το Ubuntu 'swap,home,boot κ.α' και τον χώρο που χρησιμοποιείται  
          12. Θέλω να δω τις πληροφορίες των pci/usb/audio/system drivers συσκευών 
          13. Εμφάνιση των TCP/UDP port's
          14. Εμφάνιση των υπηρεσιών (services) του υπολογιστή
          15. Θέλω να βρώ κάποιο-α αρχείο-α καθώς και στον φάκελο στον οποίο βρίσκονται
          16. Θέλω να δω ποιά προγράμματα εκτελούνται αυτή την στιγμή και τις εξαρτήσεις τους 

## Περιγραφή

Αυτό το πρόγραμμα βοηθάει με ένα φιλικό μενού στο τερματικό τον χρήστη του ubuntu να κάνει τις πιο βασικές λειτουργίες 

Κάθε λειτουργιά από το μενού αποθηκεύεται ξεχωριστά σε κάποιο αρχείο καταγραφής με την σειρά .Προσοχή εάν θέλετε να κάνετε κάποια σύγκριση των αρχείων καταγραφής θα πρέπει να τα αποθηκεύετε ξεχωριστά γιατί όταν εκτελεστεί η ίδια εντολή ξανά τότε αναιρείτε η προηγούμενη εγγραφή (δεν δημιουργείτε ξεχωριστό αρχείο).

## Πως να το χρησιμοποήσω

Κατεβάστε το πρόγραμμα απο το Url παρακάτω:

https://github.com/GiwrgosAtmatsidis/Ubuntu-script-on-Greek-/archive/master.zip

Αποσυμπιέστε τον φάκελο , ανοίξτε το τερματικό και κάντε `cd` . φάκελο που κάνατε αποσυμπίεση. Έπειτα πρέπει να το κάνετε εκτελέσιμο (δείτε παρακάτω τον κώδικα)

```
chmod +x unixgadged.bash
```
και ύστερα εκτελέστε το πρόγραμμα

```
./unixgadged.bash
```

## Eξαρτήσεις 

Αυτό το πρόγραμμα δημιουργήθηκε και δοκιμάστηκε σε λειτουργικό σύστημα Ubuntu. Δεν δοκιμάστικε σε άλλα λειτουργικά συστήματα όπως το Debian.                             

## Copyright 

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.                  
