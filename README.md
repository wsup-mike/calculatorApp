## Basic Calculator with Dark Mode (Work in Progress)
![image](https://user-images.githubusercontent.com/40747156/205188194-6faf80fb-049b-4358-a22e-957861f4a53d.png) ![image](https://user-images.githubusercontent.com/40747156/205188362-70805277-14b9-4856-b722-63b4a389543a.png)

### Adapted partially from @betomoedano but includes new modifications of existing features + inclusion of various additional features:
- [x] Display all user button presses (Both numbers and operations) in secondary display before pressing = for result
- [x] Insert dark mode/light mode icon at Switch
- [x] Basic 2 number ops: When  you press an operation make sure first number does NOT yet disappear (Keep displayed)
- [x] Add additional local state to capture all history of numbers and math ops before hitting result = 
- [x] Nudge the Number Label (Misaligned for all numbers to the left)
- [ ] To chain multiple operations in succession continously adding a new number + new math operation
- [ ] When you press each math operation it will calculate so far the result to appear in primary display
- [ ] To highlight current math operation button when next pending number to still be pressed
- [ ] Add logic to (%) button
- [ ] Add logic to (+/-) button
- [ ] Add logic to back button (x)
- [x] Add (,) 1000s separator to result (To tweak helper function firstNumberDisplay)
- [x] Add (,) 1000s separator to user inputs (numbers) 
- [ ] Fix primary display (Reading only single digits after thousands separators added)
- [ ] When press = (Result will be used for next pending calculation)
- [ ] then when you press the next math operation in sequence, the former result displays in secondary display along with new math operation symbol
- [ ] After inputting 11 digits, to prevent wrapping to a next line (Keep styling fixed even when 11+ digits are entered)
- [ ] When you press a math operation, if an operation already is in local state, then to clear it out first leaving only the recent most operation



## Run / Deploy Steps
Open Terminal
```
npm start
```

## Credit / Acknowledgement
Original tutorial by: [@betomoedano](https://www.youtube.com/watch?v=_fYgGS46h2w&t=233s)
