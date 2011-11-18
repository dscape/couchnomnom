# couchnomnom

```
                                              .
                       *
         .                       .                   .
                            .               ,"`.
  .                   _____                 `..'
                 _,odO8O8888bo._         .
              ,odOoOoOoOOOO8O888bo.                  *
      *     ,dOoOoOoOoOoOO8O8O88@8@b.           .
          ,d8o:o:o:o:o:ooOoOOOO8O88@8b.
         do:o:o:o:o:o:ooooOoOO8O88@8@@@b
.       do::.:.:.:.:.::o:ooooOOOO8888@@@b           .
       .o::::.:.:.:.::::o:ooOoOO8O88@@@@@. .
    .  |::.:.. . . ..:.::o:ooOoOO8O88@8@@|
       |o::.:.. . ..:.::o:ooOoOO8O88@8@@@|
       |::.:.. . . ..:.::o:ooOoOO8O88@8@@|
       'o::::.:.:.:.::::o:ooOoOO8O88@@@@@'     .         *
        Y8::.:.:.:.:.::o:ooooOOOO8888@@@P
        `Y8:o:o:o:o:o:ooooOoOO8O88@8@@@P'
          `Y:o:o:o:o:o:ooOoOOOO8O88@8@P     .        .
 .        . `YOoOoOoOoOoOO8O8O88@8@@P'
              `YoOoOoOoOOOO8O8888@P'     .
                 `"*YO8O8888@P*"'
        .                          *             .       .

                             .                      .
    *            .                       .
```

replicate all your CouchDB databases from one host to another

## installation

install [npm][1]:
``` sh
curl http://npmjs.org/install.sh | sh
```

install `couchnomnom`

``` sh
[sudo] npm install -g couchnomnom
```

## usage

``` sh
couchnomnom user:pass@master-hostname user:pass@copy-hostname
```

that's about it.  enjoy.

## roadmap

check [issues][2]

## contribute

everyone is welcome to contribute. patches, bugfixes, new features

1. create an [issue][2] on github so the community can comment on your idea
2. fork `couchnomnom` in github
3. create a new branch `git checkout -b my_branch`
4. create tests for the changes you made
5. make sure you pass both existing and newly inserted tests
6. commit your changes
7. push to your branch `git push origin my_branch`
8. create an pull request

## this is major tom to ground control

```
                                       _,'/
                                  _.-''._:
                          ,-:`-.-'    .:.|
                         ;-.''       .::.|
          _..------.._  / (:.       .:::.|
       ,'.   .. . .  .`/  : :.     .::::.|
     ,'. .    .  .   ./    \ ::. .::::::.|
   ,'. .  .    .   . /      `.,,::::::::.;\
  /  .            . /       ,',';_::::::,:_:
 / . .  .   .      /      ,',','::`--'':;._;
: .             . /     ,',',':::::::_:'_,'
|..  .   .   .   /    ,',','::::::_:'_,'
|.              /,-. /,',':::::_:'_,'
| ..    .    . /) /-:/,'::::_:',-'
: . .     .   // / ,'):::_:',' ;
 \ .   .     // /,' /,-.','  ./
  \ . .  `::./,// ,'' ,'   . /
   `. .   . `;;;,/_.'' . . ,'
    ,`. .   :;;' `:.  .  ,'
   /   `-._,'  ..  ` _.-'
  (     _,'``------''
```

* warning: rocket-ship not included.
* code: `git clone git://github.com/dscape/couchnomnom.git`
* home: <http://github.com/dscape/couchnomnom>
* bugs: <http://github.com/dscape/couchnomnom/issues>

`(oO)--',-` in [caos][3]

ascii art from [surfhome.de][4]

[1]: http://npmjs.org
[2]: http://github.com/dscape/couchnomnom/issues
[3]: http://caos.di.uminho.pt/
[4]: http://ascii-art.surfhome.de
