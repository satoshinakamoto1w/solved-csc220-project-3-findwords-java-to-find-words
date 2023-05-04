Download Link: https://assignmentchef.com/product/solved-csc220-project-3-findwords-java-to-find-words
<br>
Write      a          Java     program          name               FindWords.java             to         find      <strong>words</strong>               in         a          matrix.            The      letters              in         the       matrix             look     random,               but       there    are       several           hidden             words              in         the       matrix.            You               program          will      use       a          dictionary        (provided)       to         find      all        the       hidden    words,             and      print    them    out.      For       example,         you      will      find      a          file               0606matrix     on        Canvas,            it          reads:

Here,      the       first      number           6          is          the       number           of         rows,    the       second               number           6          is          the       number           of         columns.          The      program          name      is          FindWords.java.            We       type     the       following         command

%java FindWords &lt; 0606matrix

The         result               will      be:

the he hew ox box ox so




The         first      word    “the”    is          indicated         in         the       following         graph.

The         word    “he”     is          indicated         in         the       following         graph.

The         word    “hew”              is          labeled            in         the       following         graph.

Similarly,            you      can      locate              the       other    words              in         the       matrix.            Please     note    that      when    you      are       trying               to         find      the       words              in         the               matrix,            you      only     consider          the       situation          where              letters              are               on        the       SAME               row.     The      letters              of         the       same    word    must    be               adjacent          to         each    other,              from    left       to         right.    In         this      project,               we       do        not       consider          the       situation          that      letters              lying    out       vertically            or         diagonally.      For       example,         the       following        combination    is          <strong>not</strong>               considered      in         this      project.







<strong>How        to        determine      a          sequence        of         letters             is          a          word?             </strong>The               provide            skeleton           code    reads               strings             (each               is          a          word)      from    file       “<em>words</em>”           and      saves    these    strings             to         an        array    called               <em>wordlist</em>.          To        determine       whether           a          sequence         of         letters              is               a          word    or         not,      the       program          compares        the       sequence         of         letters     (it         is          a          string)              against            the       elements         of         array    <em>wordlist</em>.               If          there    is          a          match,             then     this      sequence         of         letters              is               a          word.




<strong>Can         one      letter               be        counted          as         a          word?             </strong>NO.      In         our       project,               we       assume            each    word    has       at         least    two      letters.




<strong>How        can      I           compare         two     strings             are       equal               or        not?                </strong>Use               the       equals()           method            in         String               object.             For       example,         if               you      have    two      strings             x          and      y.         If          they     have    the       same    values,    x.equals(y)       will      return              Boolean           value    true.    If          not,      it          returns               false.




<strong>How       can      I           read    the      matrix             in         my       program?</strong>        You      can      use       Scanner              class,    such     as                     Scanner           scan     =          new     Scanner(System.in);

Once       the       Scanner           object              is          generated,      you      can      use       scan.nextInt()               to         read     an        integer.           You      can      also      use       scan.next()      to         read     a               token               (imagine          it          is          a          letter               in         this      project,            but               Java     treats               each    token               as         a          String               instead            of         a               char).               Once    you      get       the       token               (pointed           by        a          String               variable,          such     as         myIn),              then     you      can      use       myIn.charAt(0)            to               get       the       first      letter               as         a          char.    The      letters              in         the       matrix    can      be        saved               to         a          2D        array,              which               can      be        char        data     type     or         String               data     type.    It          is          your     choice.

<strong>               </strong>