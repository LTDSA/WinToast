# WinToast

Implement toast on Windows

## Usage

Create a WinToast.ini under the directory where WinToast run. The content should be like this:

```ini
[Toast]
Content=Hello World!
Width=200
Timeout=3000
Rounded=True
Background=Black
```

In this config file:

- Content: Toast content
- Width: Toast width (default=200)
- Timeout: The time the toast to show (the unit is ms) (default=3000)
- Rounded: Whether the toast has rounded or not (default=True)
- Background: The background color of the toast, supports black, red, green and blue (default=Black)

## To-do

- [ ] Customizable position
- [x] Customizable shape
- [ ] Multi-line content
- [x] Colorful background
- [ ] Status logo
