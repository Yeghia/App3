There seems to be a rendering issue with Indian locale.

Th following code snipppet demonstrates the problem, the MinWidth=0 seems to be the culporit.
        <StackPanel Orientation="Vertical" BorderBrush="Black" BorderThickness="1" CornerRadius="12">
            <ToggleSwitch IsOn="True" FontWeight="Normal" FontSize="24" Width="Auto" MinWidth="0"/>
            <ToggleSwitch IsOn="True" FontWeight="Normal" FontSize="24" Width="Auto" />
        </StackPanel>

        ![Capture](https://github.com/user-attachments/assets/cb036031-3fb7-402a-87c9-484270c54023)