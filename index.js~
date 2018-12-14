export default {
    install(Vue, options){
        let loger = function(args, success = true){
            let color = 'rgba(51, 171, 129, 1)';
            if(!success) color = 'rgba(236, 126, 129, 1)';
            console.log(
                '%c     Loger data by WebSBK!     ',
                'background: ' + color + '; color: #fff; font-weight:bold;',
            );
            for(var i = 0; i < args.length; i++)
                console.log(
                    '%c  #' + i + '  ',
                    'background: ' + color + '; color: #fff; font-weight:bold;',
                    JSON.parse(JSON.stringify(args[i]))
                );
            console.log(
                '%c           End Loger!          ',
                'background: ' + color + '; color: #fff; font-weight:bold;',
            );
        };
        Vue.prototype.$loger = {
            info: function(){
                loger(arguments);
            },
            fail: function(){
                loger(arguments, false);
            }
        }
    }
}

