# Hanekokoro Fonts

Personal Iosevka builds.

* `Hanekokoro Mono`: Base font variant.
* `Hanekokoro Mono-E`: A variant of Hanekokoro Mono with only extended font.
* `Hanekokoro Sans`: Modified Iosevka Aile.

## Font variant

All fonts apply the following variant config:

```toml
[buildPlans.*]
spacing = "fontconfig-mono"
serifs = "sans"
noCvSs = true
exportGlyphNames = false

  [buildPlans.*.variants]
  inherits = "ss10"

    [buildPlans.*.variants.design]
    one = "no-base-long-top-serif"
    three = "flat-top-serifless"
    six = "closed-contour"
    eight = "crossing"
    nine = "closed-contour"
    zero = "tall-slashed"
    capital-b = "standard-interrupted-serifless"
    capital-c = "unilateral-inward-serifed"
    capital-g = "toothless-corner-serifless-hooked"
    capital-j = "flat-hook-serifed"
    capital-k = "curly-serifless"
    capital-l = "serifless"
    capital-p = "open-serifless"
    capital-q = "crossing-baseline"
    capital-r = "curly-open-serifless"
    capital-s = "unilateral-inward-serifed"
    capital-w = "rounded-vertical-sides-serifless"
    capital-x = "curly-serifless"
    capital-y = "curly-serifless"
    capital-z = "curly-serifless"
    a = "single-storey-earless-rounded-tailed"
    b = "toothless-corner-serifless"
    c = "unilateral-inward-serifed"
    d = "toothless-corner-serifless"
    e = "rounded"
    f = "serifless"
    g = "single-storey-flat-hook-earless-rounded"
    i = "serifed-diagonal-tailed"
    j = "diagonal-tailed-serifed"
    k = "curly-serifless"
    l = "serifed-diagonal-tailed"
    m = "earless-rounded-double-arch-short-leg-serifless"
    n = "earless-corner-straight-serifless"
    p = "earless-corner-serifless"
    q = "earless-corner-diagonal-tailed-serifless"
    r = "serifless"
    s = "unilateral-inward-serifed"
    t = "diagonal-tailed"
    u = "toothless-rounded-serifless"
    x = "curly-serifless"
    y = "cursive-serifless"
    capital-eszet = "corner-serifless"
    long-s = "flat-hook-diagonal-tailed"
    eszet = "longs-s-lig-serifless"
    lower-lambda = "curly-turn"
    lower-mu = "toothless-rounded-motion-serifed"
    lower-xi = "rounded"
    lower-phi = "straight"
    cyrl-ve = "cursive"
    tittle = "round"
    asterisk = "hex-low"
    caret = "low"
    paren = "flat-arc"
    brace = "curly-flat-boundary"
    guillemet = "curly"
    ampersand = "lower-open"
    at = "fourfold-tall"
    dollar = "through-cap"
    percent = "rings-segmented-slash"
    question = "corner-flat-hooked"
    pilcrow = "curved"
    lig-neq = "vertical"
    lig-equal-chain = "without-notch"
    lig-hyphen-chain = "without-notch"
    lig-double-arrow-bar = "without-notch"
    lig-single-arrow-bar = "without-notch"

  [buildPlans.*.ligations]
  inherits = "dlig"
```
