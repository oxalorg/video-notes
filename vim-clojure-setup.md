# Clojure Vim Setup

* Unknown unknowns

* Avoiding fancy stuff

* Linting

* REPL driven development

* Connecting to repl from vim

* Manipulating parens

## Requirements

* Opendjk-8/11
    sudo apt install default-jdk
* Clojure
    - curl -O https://download.clojure.org/install/linux-install-1.10.1.561.sh
    - chmod +x linux-install-1.10.1.561.sh
    - sudo ./linux-install-1.10.1.561.sh
* Leininininingen
    - https://leiningen.org/

## Vim plugins

* clj-kondo
    - curl -sLO https://raw.githubusercontent.com/borkdude/clj-kondo/master/script/install-clj-kondo
    - chmod +x install-clj-kondo
    - ./install-clj-kondo
    - ale

* cider-nrepl
    ```
    {:user
      {:plugins [[cider/cider-nrepl "0.25.3"]]}
    ```
* vim-fireplace
    - `cqc`: quasi repl blank line
    - `cqq`: quasi repl fill the form
    - `cpp`: push the current form to the repl
* vim-parinfer
* async-clj-omni
