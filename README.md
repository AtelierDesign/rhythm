# Rhythm.Color™
Rhythm® Color System

Developed by [**AtelierDesign**](https://atlrdsgn.com)®–
for use with [Stitches](https://stitches.dev) and [Radix-UI](https://www.radix-ui.com) Components.

<hr>

### Installation

```
yarn add @atlr-dsgn/rhythm
```
or
```
npm install @atlr-dsgn/rhythm
```

### Usage

Import Rhythm® into your project.

```
import { colors } from '@atlr-dsgn/rhythm'
```

Then use the system as tokens.

```tsx
import { styled } from '@stitches/react';

const Background = styled('div', {
    backgroundColor: '$razz5',
    color: '$ghost12'
});
```

### Example Component

```tsx 
import React from 'react';
import { Text } from 'atelier.design';


export const RhythmExample = () => {
  return (
    <>
      <Text css={{ color: '$moon9' }}>
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

<hr>

Copyright © 2022 Atelier Design Yield®

MIT License
