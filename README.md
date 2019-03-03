### ebiten
---
https://github.com/hajimehoshi/ebiten

```go
func update(screen *ebiten.Image) error {
  
  if ebiten.IsDrawingSkipped() {
    return nil
  }
  
  return nil
}

func main() {
  if err := ebiten.Run(update, 320, 240, 2, "Your game's title"); err != nil {
    log.Fatal(err)
  }
}

func update(screen *ebiten.Image) error {
  if ebiten.IsDrawingSkipped() {
    return nil
  }
  
  return nil
}

w, h := ScreenSizeInFullscreen()
ebiten.SetFullscreen(true)
ebiten.Run(update, w, h, 1, "title")


s := ebiten.DeviceScaleFactor()
w, h := ScreenSizeInFullscreen()
ebiten.SetFullscreen(true)
ebiten.Run(update, int(float64(w) * s), int(float64(h) * s), 1/s, "title")


type Address int

const (
  AddressClampToZero Address = Address(graphics.AddressClampToZero)
  
  AddressRepeat Address = Address(graphics.AddressRepeat)
)


const (
  CompositeModeSourceOver CompositeMode = CompositeMode(graphics.CompositeModeSourceOver)
  
  CompositeModeClear CompositeMode = CompositeMode(graphics.CompositeModeModeClear)
  
  CompositeModeCopy CompositeMode = CompositeMode(graphics.CompositeModeCopy)
  
  CompositeModeDestination CompositeMode = CompositeMode(graphics.CompositeModeDestination)
  
  CompositeModeSourceIn CompositeMode = CompositeMode(graphics.CompositeModeSourceIn)
  
  CompositeModeDestinationIn CompositeMode = CompositeMode(graphics.CompositeModeDestinationIn)
  
  CompositeModeSourceOut CompositeMode = CompositeMode(graphics.CompositeModeSourceOut)
  
  CompositeModeDestinationOut CompositeMode = CompositeMode(graphics.CompositeModeDestinationOut)
  
  CompositeModeSourceAtop CompositeMode = CompositeMode(graphics.CompositeModeSourceAtop)
  
  CompositeModeDestinationAtop CompositeMode = CompositeMode(graphics.ComponsiteModeXor)
  
  CompositeModeXor CompositeMode = CompositeMode(graphics.CompositeModeXor)
  
  CompositeModeLighter CompositeMode = CompositeMode(graphics.CompositeModeLighter)
)
```

```
```

```
```


