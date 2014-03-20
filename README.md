#ko-ki/dotfiles
---
* ###Brewfile (for homebrew/homebrew-cask)
####how to use
    ```
    ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"
    
    #シンボリックリンク/Caskroomの場所を変更する場合 環境変数を変更
    export HOMEBREW_CASK_OPTS="--appdir=/Applications --caskroom=/usr/local/Caskroom
        
    # Brewfileが置かれたディレクトリに移動
    brew bundle
    ```
