# Simplex Model Number Checker
## History
The Simplex Model Number Checker was originally developed by Andrew Davis, known on YouTube as NewAgeServerAlarm back in 2012 with a video titled [Fire Alarm Buyers' Guide Part 1: Notification Appliances](https://www.youtube.com/watch?v=eSUUNoW0h_Q). While the link in the video description is no longer valid, the tool has been moved to The Fire Panel, LLC's website and can still be used at [this link](https://www.thefirepanel.com/wiki/ndevices/simplexmnc/) today.

## How it Works
The Simplex Model Number Checker is used to determine compatibility of Simplex Horn / Strobes. They can be broken down to the following categories:

- FreeRun: When power is applied, both the horn and strobe will run
- Selectable: When power is applied, the horn will run always. The strobe can flash on it's own, or with SmartSync depending on a DIP Switch setting
- Syncable: Horn will operate when power is applied, but strobe will only flash when power is removed
- SmartSync: Requires a compatible Simplex Panel, or a SmartSync module such as the 4905-9938 to operate Horn or Strobe
- Addressable: For use only with high-end Simplex Panels, such as the 4100U
- ES: Requires a Simplex 4007ES, 4010ES, or 4100ES for operation

When a user enters a value for a device model number, the checker compares that to values in the list and returns the matched device type.

## Do we have something missing or wrong in the list?
If you have a GitHub account, you are very welcome to fork our repository, make the corrections, and [open a pull request](https://github.com/TheFirePanel/SimplexModelChecker/compare)!

If you ahve a GitHub account but aren't able to make the pull request, please feel free to [create a new issue](https://github.com/TheFirePanel/SimplexModelChecker/issues/new/choose) for us to resolve.

And if you don't have a GitHub account, please feel free to contact us via email at [admin@thefirepanel.com](mailto:admin@thefirepanel.com).