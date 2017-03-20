# Παρουσίαση κορμός 

Η παρουσίαση αυτή αποτελεί ένα κορμό για να ξεκινήσετε την επόμενη παρουσίαση που ετοιμάζετε σε
reveal.js. 

# Πως να ξεκινήσετε

Κατεβάστε την παρουσίαση και επεξεργαστείτε το αρχείο [index.html](index.html). Όλη η παρουσίαση είναι ουσιαστικά ένα html αρχείο. Περισσότερες πληροφορίες στον ιστότοπο του reveal-js. 

Τροποποιήστε κατ' ελάχιστον τα στοιχεία που αφορούν το υποσέλιδο της παρουσίασης:
```html
<div id="presentationfooter">
    <small>
    Μάρτιος 2017 
    | Ομάδα Ανάπτυξης Λογισμικού Ανοικτού Κώδικα 
    | <a href="http://ostmgmt.minedu.gov.gr">ostmgmt.minedu.gov.gr</a> 
    | <a href="https://git.minedu.gov.gr">git.minedu.gov.gr</a> 
    | <a href="mailto:osteam@minedu.gov.gr">osteam@minedu.gov.gr</a> 
    </small>
</div>
```

Κάθε σελίδα της παρουσίασης πρέπει να εισάγετε εντός ενός `section`, όπως για παράδειγμα:
```html
<section>
    <h2>Δείγμα #1</h2>
    <pre><code class="php">
use Gr\Gov\Minedu\Osteam\Slim\Client;
use Gr\Gov\Minedu\Osteam\App\Extract;

$client = new Client($settings);
$app = new Extract($client, $settings); 
    </code></pre>
</section>
```

# Περισσότερες πληροφορίες 

Η παρουσίαση βασίζεται στο [reveal-js](http://lab.hakim.se/reveal-js) ([github](https://github.com/hakimel/reveal.js)). 

Για την έγχρωμη σύνταξη κώδικα χρησιμοποιείται το [highlight.js](https://highlightjs.org/).

Κύριες γραμματοσειρές [Ubuntu,  Ubuntu Mono](https://fonts.google.com/?query=ubuntu).

# Συνεισφορά

Σε περίπτωση που κάνετε διορθώσει ή επεκτάσεις, κάντε ένα pull request. 
:) 
