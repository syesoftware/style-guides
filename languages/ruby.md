# Ruby Style Conventions

## Table of Contents

  1.  [Indentation](#indentation)
  1.  [Inline Code](#inline-code)

## Indentation

* Use soft-tabs set to 2 spaces.

```ruby
class Pokemon
∙∙def weakness
∙∙∙∙# Handles weakness
  end
end
```

## Inline Code

* Never leave trailing whitespace.

* Use spaces around operators; after commas, colons, and semicolons;
and around `{` and before `}`.

```ruby
sum = 1 + 1
a, b = 1, 2
a > sum ? '2 is now greater than 1' : 'You cannot math'
[1, 2, 3].each { |e| puts e }
```

* No spaces after `(`, `[` or before `]`, `)`.

```ruby
some(arg).other
[1, 2, 3].length
```
