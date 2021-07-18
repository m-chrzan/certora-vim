# Vim syntax highlighting for Certora

`certora.vim` provides Vim syntax highlighting directives for Certora prover's
specification language. Put it in your `~/.vim/syntax/` directory, and add a
`~/.vim/ftdetect/certora.vim` file with

    autocmd BufNewFile,BufRead *.spec set filetype=certora
    
for autodetection of the spec filetype.
