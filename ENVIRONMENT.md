umask 022
export EDITOR=nano
export VISUAL=nano

export NINJA_SUMMARIZE_BUILD=1
export NINJA_STATUS="[%r processes, %f/%t @ %o/s | %e sec. ] "
export PATH=/home/alex/depot_tools:$PATH

export DEPOT_TOOLS_UPDATE=0
export DEPOT_TOOLS_WIN_TOOLCHAIN_BASE_URL=/home/alex/chromium/win/
export GYP_MSVS_HASH_3bc0ec615cf20ee342f3bc29bc991b5ad66d8d2c=548e1677e024860c1de859075bce5c068d1bca73

alias gsync='gclient sync --with_branch_heads --with_tags -f -R -D'
alias gclean='git clean -ffd'

alias 69='git checkout tags/69.0.3497.128'
