$ ( ôóíêöèÿ () {
    êîíñîëü . log (from);
    var from =  $ ( ' #from ' );
    var to =  $ ( ' #to ' );
    var func =  $ ( ' #func ' );
    var out =  $ ( ' #output ' );
    $ ( ' #plot ' ). click ( ôóíêöèÿ ( ñîáûòèå ) {
        ñîáûòèå . preventDefault ();
        var x =  parseFloat ( from . val ());
        var end =  parseFloat ( to . val ());
        âàð = (êîíåö - ?) /  100 ;
        startAnim (x, end, dx, func . val ());
    });

    ôóíêöèÿ  startAnim ( x , end , dx , func ) {
        var array = [];
        var interval =  setInterval ( function () {
            êîíñîëü . log (ìàññèâ);
            ìàññèâ . push ([x, eval (func)]);
            $ . plot (out, [{label : func, data : array}]);
            x + = dx;
            end - = dx;
            if (end <  0 ) clearInterval (èíòåðâàë);
        }, 100 );
        èíòåðâàë âîçâðàòà ;
    }
});
