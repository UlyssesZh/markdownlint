<!-- MD041 is not triggered -->
# Test block comments
<!-- MD022 is not triggered -->

- So this list is still regarded as wrapped by blank lines
- goes on
<!-- Even if the comment is very long, it does not trigger MD013 because it is ignored -->

<!-- A block comment can contain
multiple lines
like this -->
```plaintext
same with code blocks, MD031 is not triggered
<!-- Block comments in code blocks are not ignored, so a lone line like this can still trigger MD013 -->
```

Inline<!-- comments --> are not ignored, so a long line like this can also trigger MD013

<!-- Because this comment is ignored, the two line endings trigger MD012 -->

<!-- and MD047 -->
