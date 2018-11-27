# XamarinForms-TimePickerSeconds
Bindable timepicker control with seconds for Xamarin Forms iOS

From the [StackOverflow question](https://stackoverflow.com/questions/35931470/timepicker-with-seconds/)

#### XAML Usage
``` xml
<myControls:MyTimePicker SelectedTime="{Binding SelectedTime}" />
```

Note that this code is dependent on [XForms](https://github.com/XLabs/Xamarin-Forms-Labs) to get the device screen size, because that's the framework that I'm using for my project, but it can easily be modified.
