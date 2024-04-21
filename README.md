# Iosevka Minoko

Personal Iosevka builds.

* `Iosevka Minoko`: Base font variant.
* `Iosevka Minoko-E`: A variant of Iosevka Minoko with only extended font.
* `Iosevka Minoko Term`: The Iosevka Minoko version of Iosevka Term.
* `Iosevka Aile Minoko`: Iosevka Aile with the variant config of Iosevka Minoko.

## Font variant

All fonts apply the following variant config:

```toml
[buildPlans.*.variants]
inherits = "ss10"

  [buildPlans.*.variants.design]
  capital-c = "unilateral-inward-serifed"
  capital-g = "toothless-corner-serifless-hooked"
  capital-j = "flat-hook-serifed-both-sides"
  capital-k = "curly-serifless"
  capital-l = "serifless"
  capital-p = "open-serifless"
  capital-q = "crossing-baseline"
  capital-r = "curly-open-serifless"
  capital-s = "unilateral-inward-serifed"
  capital-x = "curly-serifless"
  capital-y = "curly-serifless"
  a = "single-storey-earless-rounded-tailed"
  b = "toothless-corner-serifless"
  c = "unilateral-inward-serifed"
  d = "toothless-corner-serifless"
  e = "rounded"
  f = "serifless"
  g = "single-storey-flat-hook-earless-rounded"
  i = "serifed-diagonal-tailed"
  j = "diagonal-tailed-serifed"
  k = "curly-top-left-serifed"
  l = "serifed-diagonal-tailed"
  m = "earless-rounded-double-arch-tailed-serifless"
  n = "earless-corner-tailed-serifless"
  p = "earless-corner-serifless"
  q = "earless-corner-diagonal-tailed-serifless"
  r = "serifless"
  s = "unilateral-inward-serifed"
  t = "diagonal-tailed"
  u = "toothless-rounded-serifless"
  x = "curly-serifless"
  y = "cursive-serifless"
  eszet = "sulzbacher-bottom-serifed"
  lower-lambda = "curly-turn"
  lower-mu = "toothless-rounded-motion-serifed"
  zero = "tall-slashed"
  paren = "flat-arc"
  brace = "curly-flat-boundary"
  at = "fourfold-tall"
  dollar = "through-cap"
  percent = "rings-segmented-slash"
  question = "corner"
  pilcrow = "high"
  lig-neq = "vertical"
  lig-equal-chain = "without-notch"
  lig-hyphen-chain = "without-notch"
  lig-double-arrow-bar = "without-notch"
  lig-single-arrow-bar = "without-notch"

[buildPlans.*.ligations]
inherits = "dlig"
```