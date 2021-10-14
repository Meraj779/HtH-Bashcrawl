1  cat scroll
    2  cd entrance
    3  cd treasure
    4  cd armoury
    5  cd cellar
    6  ls -f
    7  cd armoury
    8  ls -f
    9  ./ potion
   10  ./potion
   11  export HP=15
   12  ./treasure
   13  export I=sword,$I
   14  echo $I
   15  ./treasure
   16  export I=sword,$I
   17  cat scroll
   18  cd ..
   19  ls -f
   20  ./treasure
   21  export I=amulet,$I
   22  cat scroll
   23  ls -f
   24  cd ..
   25  cd armoury
   26  cd cellar
   27  ls -f
   28  scroll
   29  ./scroll
   30  cat scroll
   31  cd chamber
   32  ./chamber
   33  cd armoury
   34  ./chamber
   35  cd chamber
   36  ls -f
   37  cat scroll
   38  ./spell
   39  ls -f
   40  ./treasure
   41  export I=coins,$I
   42  echo $I
   43  cat scroll
   44  ls -f
   45  cd ..
   46  cd ..
   47  cd ..
   48  cd rift
   49  cd .rift
   50  ls -f
   51  ./box
   52  ls -f
   53  ./spire/
   54  ./box*
   55  cd spire
   56  ls -f
   57  ./mezzanine
   58  mezzanine/
   59  ./mezzanine/
   60  cd ..
   61  cd ..
   62  cd cellar
   63  cd armoury
   64  cd chamber
   65  ./statue
   66  y
   67  echo $
   68  ls -f
   69  ./potion
   70  cd ..
   71  ./potion
   72  echo $HP
   73  ./treasure
   74  export I=sword,$I
   75  echo $I
   76  ./scroll
   77  cd ..
   78  cd ..
   79  cd chapel
   80  ./altar
   81  ./scroll
   82  ./fountain
   83  cd aviary
   84  cd courtyard
   85  ./fountain
   86  ./rags
   87  export I=rags,fish,$I
   88  cd aciary
   89  cd aviary
   90  ./crystal
   91  I=crystal,$I
   92  ./penguin
   93  export I=$fish
   94  export I=$(sed "s/fish//; s/,,/,/" <<< $I)
   95  ./scroll
   96  cd hall
   97  ./monster
   98  cd library
   99  ./scroll
  100  ./tomoe
  101  ./tome
  102  cd ..
  103  cd ..
  104  cd ..
  105  cd..
  106  ./altar
  107  cd ..
  108  ./alta
  109  ./altar
  110  cd ..
  111  ./vault
  112  ./vault
  113  ls -ff
  114  ls -f
  115  vault/
  116  cd vault
  117  ./glass
  118  cd ..
  119  cd cellar
  120  cd chamber
  121  ./chamber
  122  cd chamber
  123  cd armoury
  124  cd chamber
  125  pwd
  126  ./scroll
  127  ./spell
  128  ./statue
  129  echo $
  130  ./potion
  131  ./treasure
  132  export I=coins,$I
  133  cd ..
  134  cd ..
  135  cd ..
  136  history
  137  cd .
  138  cd ..
  139  history
  140  history > dungeonhistory.md
  141  echo history >> dungeonhistory.md
  142  touch dungeonhistory.md
  143  history > Dungeonhistory.md
  144  history