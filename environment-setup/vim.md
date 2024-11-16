# Vim

For now, I use Vim to write my code on WSL (that's because [CS1010](https://wenbo-notes.gitbook.io/cs1010-notes) uses vim :joy:). So, I decide to migrate the vim setup from CS1010 on my pc.

## Ubuntu

Since setting up vim and managing plugins on Windows is tedious and not elegant. I decide to use Vim on my WSL (Ubuntu). Below are the necessary configuration files:

{% @github-files/github-code-block url="https://github.com/mendax1234/Vim-config" %}

### Steps

Copy the `.vimrc` to your home directory. You can do this by using

```bash
git clone https://github.com/mendax1234/Vim-config.git
```

to clone the whole repository somewhere on your pc, `cd` to the repo's root directory and then use

```bash
cp ./.vimrc .
```

to copy `.vimrc` to your home directory (`~`)

Then, copy the `.vim` folder to your home directory also using&#x20;

```bash
cp -r ./.vim/ .
```

Now, the setup is done!
