# small_scripts
Small scripts I wrote that ease some dev roles. Feel free to use them, contribute new or improved versions or whatever. 

## madness
"Madness is doing the same thing over and over again, expecting the result to change."

Or to put it into some nicer words, this little one-liner runs the command you give it as a parameter until it returns a nonzero exit code. 

### Sample

```
madness rspec spec/features/phony_js_test.rb
```
will run this particular file until the test suite fails. 

If you actually need to use this, re-evaluate your life choices.
