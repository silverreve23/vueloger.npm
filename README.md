# VueLoger

<p align="center">
    <img src="https://lh3.googleusercontent.com/ol7W4x-UfQw0Umy1xN2fIsGjLB2Mk1JIwxhE9VIWUipVABiQAbi3qAaIWqEhvy_ylLkREjZqLgQJTFcdO1CzL4r8kJ-Q4xvKzeRYAJ4d7Is-87ESnf3HUxmCs3vZh3Y1Z45BtG_LcHrsNp17mNGjxJyCz5iu_TcXojZts8phavepjvI3icHuulO3L_Ht_zYtV9TQSskE_x656J2qt3FDvvbXmAqmEf8CTU6XjQnEciXwmFBdzvVWSx_7tSUe6XVZRGGcFN8vAVod3ZKtQpvh_OQESn5-f3sFyvMIsuVJldU-hbtIf5Itl3KgDPb30UO2irjWmW6G70LV4LEDEEb1ih3R26eLpF4mQXsROwkNf1jC8EGm8IjitKQF1N7x_SffWp2ANsfQtATbdOGNbFQXcm5Cmhf_E5_p5JKHD2rAK2oIvX8HR-PVeWN6_CFBPVKrL4DnkK18GA1c8a6cIKr02QuymNUEXhIraw4oby8xPr_GFuTwO4HoJztlulxCIyNXhEEsORKxLNftEXGHjXdXkJZiwhOROwgkRYijGPjDZHPrWczrhDVAxMmQdCjHotkGjMrwZ3F9LzXc59BA-2rUTyuHYKk1hBfRB1xX1CQokgdJn8chKLnC06YudHRHM6gD9RvU4RuWj3nrjaWuWImbETaK=w522-h222-no" width="546">
</p>

<p align="center">
    Loger vue plugin for console.log().
</p>

## How to install

Run this command in terminal

	npm i vue-loger

Include plugin in <b>app.vue</b> 

```javascript

import Loger from 'vue-loger';

Vue.use(Loger);

```
and try run loger:

```javascript

    this.$loger.info(true, 'success', 100, {}, []);
    this.$loger.fail(false, 0);

```

