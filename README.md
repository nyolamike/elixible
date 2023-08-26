# ELIXIBLE
The Kings Version

## Genesis

### Chapter 1 - Forging Order from the Chaos: 

#### A Tale of Elixir's Version Management and Tool Ascendancy

$^1$ Behold, for it is decreed that every Elixir iteration shall be yoked to an incarnation of OTP/Erlang, akin to harmonious souls in a celestial dance.

$^2$  In thy journey through code's realms, thou shalt oversee diverse projects, each on varying Elixir-OTP/Erlang forms. 

$^3$ To navigate, heed the sermon of version managers like [asdf](https://asdf-vm.com/guide/getting-started.html#_2-download-asdf), kiex, and kerl – tools crafted for harmonious orchestration.

```bash
git clone https://github.com/asdf-vm/asdf.git ~/.asdf --branch v0.12.0
```

$^4$ For the beholders of affection for the brew of home, thou mayst partake of its use; yet verily, the path of wisdom commends the official git method as the chosen way.

```bash
brew install asdf
```
$^5$ When thou dost asdf, recall that its utility blooms with the installation of a [plugin](https://github.com/asdf-vm/asdf-elixir). With this, tools shall be summoned and their versions managed

```bash 
asdf plugin-add elixir https://github.com/asdf-vm/asdf-elixir.git
```

$^{5.2}$ When the zsh, in its manner, doth declare "`zsh: command not found: asdf`," extend thy helping hand by embarking upon the following counsel: 

$^{5.3}$ dost thou open `vim ~/.zshrc` and therein scribe these words:

```
. ~/.asdf/asdf.sh
. ~/.asdf/completions/asdf.bash
```

$^{5.4}$ Know ye, the symbol ~ is a beacon to thy dwelling directory, while for some, it may be $Home. 

$^{5.5}$ Once these changes are wrought, bid farewell to the current terminal and usher in a new abode. Lo, the command "asdf" shall find its rightful dwelling therein.

$^6$ Following, embark upon the task of installing the ASDF plugins for Elixir and Phoenix, for in the realm of knowledge, it is well acknowledged that Phoenix holds a place most cherished.
```
asdf plugin-add erlang
asdf plugin-add elixir
asdf plugin-add nodejs
```

$^{6.2}$ Node, perchance, hath sown seeds of doubt within thy heart, yet mark ye well that it serveth certain of Phoenix's resources. Nonetheless, Phoenix hath ascended to a realm of LiveView wherein it can forsaketh the need for the tools of Nodejs in its construction.

$^{6.3}$ Behold, gaze upon the words of [cogini](https://www.cogini.com/blog/using-asdf-with-elixir-and-phoenix/), though they may bear the touch of time's passage, their structure remains steadfast.

$^{6.4}$ In the annals of wisdom, the script of ***[cogini](https://www.cogini.com/blog/using-asdf-with-elixir-and-phoenix/)*** shines as a guide, illuminating the path to asdf's build dependencies, beware though that time may have left its mark upon some commands.


$^7$ Projects adorned with a `.tool-versions` parchment file can summon the required realm of execution by uttering the incantation:
```
asdf install
```