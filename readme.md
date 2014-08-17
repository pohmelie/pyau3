# pyau3
Autoit3 bindings for Python3 via AutoItX.dll.
## Usage
```python
import pyau3


au3 = pyau3.autoit()

# setting options
au3.AU3_AutoItSetOption("SendKeyDelay", 50)
au3.AU3_AutoItSetOption("SendKeyDownDelay", 50)
au3.AU3_AutoItSetOption("SendCapslockMode", 0)
au3.AU3_AutoItSetOption("WinTitleMatchMode", 2)
au3.AU3_AutoItSetOption("MouseClickDownDelay", 25)
au3.AU3_AutoItSetOption("MouseCoordMode", 2)
au3.AU3_AutoItSetOption("PixelCoordMode", 2)

# working with "classic" autoit functions
au3.AU3_WinActivate("caption")
au3.AU3_Send("{F2}")
```
