# Disable Inspect

The package disables the inspect elements feature of the browser by disabling right-click and shortcut keys which can open the elements inspector for the website.

## Installation

We can use the package in two ways.

1. By directly inserting the javascript file in the DOM using the script tag and calling the `disableInspect` method.

```
    <script src="https://cdn.jsdelivr.net/npm/disable-inspect@1.0/dist/main.js"></script>
    <script>disableInspect();</script>
```

2. Using the npm, we can install in the package and using in any of the preferred libraries or framework. Use the command `npm i disable-inspect` to install the package and then

```
import { disableInspect } from "disable-inspect";

disableInspect();
```

## Credits

- [Abhishek Prakash](https://github.com/abhishek6262)

## Contributing

Please feel free to fork this package and contribute by submitting a pull request to enhance the functionalities. I will appreciate that a lot. Also please add your name to the credits.

Kindly [follow me on twitter](https://twitter.com/_the_shade)!

## Support

Moreover, To keep this and my other open source projects ongoing You can also support me on Patreon by clicking on the button below.

[<img src="https://c5.patreon.com/external/logo/become_a_patron_button.png">](https://www.patreon.com/bePatron?u=5563585)

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
