---
layout: page
tags: [api]
title: Fyne API fyne
---

# fyne
---
```go
import "fyne.io/fyne"
```

## Usage

#### type SecondaryTappable

```go
type SecondaryTappable interface {
	TappedSecondary(*PointEvent)
}
```

SecondaryTappable describes a CanvasObject that can be right-clicked or long-tapped.
