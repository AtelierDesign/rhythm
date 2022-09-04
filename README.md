# Rhythm.Color™
Rhythm® Color System

Developed by [**AtelierDesign**](https://atlrdsgn.com)®–
for use with [Stitches](https://stitches.dev) and [Radix-UI](https://www.radix-ui.com) Components.

<hr>

### Installation

`yarn add rhythm.color`
or
`npm install rhythm.color`

### Usage

Import Rhythm® into your project.

` import { colors } from 'rhythm.color' `

Then use the system as tokens.

` $rhythm(x) `

### Example Component

```tsx 
import React from 'react';
import { Text } from 'atelier.design';


export const RhythmExample = () => {
  return (
    <>
      <Text css={{ color: '$rhythm2' }}>
        Hi, from Rhythm® Color
      </Text>
    </>
  )
};

```

### The Colours

##### **R** = $raspberry or $razz
##### **H** = $heaven
##### **Y** = $yllw, $yello, or $yellow
##### **T** = $tango
##### **H** = $heliotrope or $helio
##### **M** = $mauve
##### **C** = $capri



Copyright © 2022 Atelier Design Yield®

MIT License
