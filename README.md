# WinToast

Implement toast on Windows

## Usage

Create a WinToast.ini under the directory where WinToast run. The content should be like this:

```ini
[Toast]
Content=Hello World!
Width=200
Timeout=3000
```

In this config file:

- Content: Toast content
- Width: Toast width (default=200)
- Timeout: The time the toast to show (the unit is ms) (default=3000)

## To-do

- [ ] Customizable position
- [ ] Customizable shape
- [ ] Multi-line content
- [ ] Colorful background
- [ ] Status logo
