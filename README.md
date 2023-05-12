# bin

### Usage
How to use this script?
Just put the files on your `$PATH`
```sh
echo ${PATH//://\\n}
```
or this command:

```sh
git clone --depth=1 https://github.com/lime-desu/bin.git ~/.local/bin/
if [[ -f ~/.zshrc ]]; then
	echo "export PATH=\$HOME/.local/bin:\$PATH" >>~/.zshrc
else
	echo "export PATH=\$HOME/.local/bin:\$PATH" >>~/.profile
fi
```

<details>
<summary><strong><a href="https://github.com/lime-desu/bin/blob/main/$">$</strong></a></summary>

  Ever run into `bash: $: command not found` error?
  This lazy copy paste cringe script fixes that.

  ![image $](https://github.com/lime-desu/bin/assets/114978689/10c562a3-570b-44b6-bdc4-885dd1f17e41)

</details>

<details>
<summary><strong><a href="https://github.com/lime-desu/bin/blob/main/colorscript">colorscript</strong></a></summary>

  A colorscript but (currently?) only color blocks and panes are available.

  ![image colorscript](https://github.com/lime-desu/bin/assets/114978689/c7cf9ede-5b78-4411-b50c-817ff33c80cc)

</details>

<details>
<summary><strong><a href="https://github.com/lime-desu/bin/blob/main/dnfzf">dnfzf</strong></a></summary>

  Interactive dnf package manager (my very first written script btw 100% written by hooman)

  ![image dnfzf](https://github.com/lime-desu/bin/assets/114978689/97252b38-44d6-4e2d-a9c5-df5ae8ed88fc)

</details>

<details>
<summary><strong><a href="https://github.com/lime-desu/bin/blob/main/donut">donut</strong></a></summary>

  Spinning Ascii Donut (colored). Source code? Idk stolen from [here](https://github.com/PROxZIMA/.dotfiles/blob/master/.local/bin/donut).

  ![gif donut](https://github.com/lime-desu/bin/assets/114978689/43bbf9a1-67db-4aea-8924-a7a770b79bf5)

</details>

<details>
<summary><strong><a href="https://github.com/lime-desu/bin/blob/main/gh-dl">gh-dl</strong></a></summary>

  Another fzf script that will download releases from GitHub repositories

</details>

<details>
<summary><strong><a href="https://github.com/lime-desu/bin/blob/main/lofi">lofi</strong></a></summary>

  Stream/Listen lofi music from [LofiGirl](https://www.youtube.com/@LofiGirl) or either to [fccCodeRadio](https://coderadio.freecodecamp.org/)

</details>

<details>
<summary><strong><a href="https://github.com/lime-desu/bin/blob/main/mkdesk">mkdesk</strong></a></summary>

  Simple script to create desktop entries for applications. (Since GNOME doesn't have this basic feature)

</details>

<details>
<summary><strong><a href="https://github.com/lime-desu/bin/blob/main/nf-dl">nf-dl</strong></a></summary>

  Nerd Font install and download (fzf script).

  ![image nf-dl](https://github.com/lime-desu/bin/assets/114978689/73d93f52-f1b5-4a2e-b8eb-e24a844f43c8)

</details>

<details>
<summary><strong><a href="https://github.com/lime-desu/bin/blob/main/nf-ls">nf-ls</strong></a></summary>

  List all and copy the nerd fonts icons (requires: wl-clipboard).

  ![image nf-ls](https://github.com/lime-desu/bin/assets/114978689/2fb0cc23-6ef9-41a3-8345-4c0bd387d30f)

</details>

<details open>
<summary><strong><a href="https://github.com/lime-desu/bin/blob/main/xkcd">xkcd</strong></a></summary>

  ![image xkcd](https://github.com/lime-desu/bin/assets/114978689/5de66e77-f86d-4705-b61f-1aadaad9d570)

</details>
