<Window x:Class="WpfApp4.MainWindow"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:local="clr-namespace:WpfApp4"
        mc:Ignorable="d"
        Title="MainWindow" Height="450" Width="800">
    <Grid>
        <Grid.ColumnDefinitions>
            <ColumnDefinition Width="252*"/>
            <ColumnDefinition Width="2*"/>
            <ColumnDefinition Width="539*"/>
        </Grid.ColumnDefinitions>

        <Image Margin="-2,10,7.6,198" Source="HMUJ9320.JPG" Stretch="Fill" RenderTransformOrigin="0.5,0.5" Grid.ColumnSpan="3">
            <Image.RenderTransform>
                <TransformGroup>
                    <ScaleTransform/>
                    <SkewTransform AngleY="0.632"/>
                    <RotateTransform Angle="-0.984"/>
                    <TranslateTransform Y="-5.296"/>
                </TransformGroup>
            </Image.RenderTransform>
        </Image>
        <TextBox Grid.ColumnSpan="3" HorizontalAlignment="Left" Height="162" Margin="4,220,-0.4,0" TextWrapping="Wrap" VerticalAlignment="Top" Width="790" RenderTransformOrigin="0.5,0.5" Text="San Francisco Bay is a shallow estuary in the US state of California. It is surrounded by a contiguous region known as the San Francisco Bay Area (often simply &quot;the Bay Area&quot;), and is dominated by the large cities of San Jose, San Francisco and Oakland.&#xD;&#xA;&#xD;&#xA;San Francisco Bay drains water from approximately 40 percent of California. Water from the Sacramento and San Joaquin rivers, and from the Sierra Nevada mountains, flow into Suisun Bay, which then travels through the Carquinez Strait to meet with the Napa River at the entrance to San Pablo Bay, which connects at its south end to San Francisco Bay. The Guadalupe River enters the bay at its southernmost point in San Jose. The Guadalupe drains water from the Santa Cruz mountains and Hamilton Mountain ranges in southernmost San Jose. It enters the bay at Alviso, a neighborhood of San Jose. It then connects to the Pacific Ocean via the Golden Gate strait. However, this entire group of interconnected bays is often called the San Francisco Bay. The bay was designated a Ramsar Wetland of International Importance on February 2, 2012.">
            <TextBox.RenderTransform>
                <TransformGroup>
                    <ScaleTransform/>
                    <SkewTransform/>
                    <RotateTransform Angle="-0.247"/>
                    <TranslateTransform/>
                </TransformGroup>
            </TextBox.RenderTransform>
        </TextBox>
        <WebBrowser x:Name="click" Grid.Column="2" HorizontalAlignment="Left" Height="28" Margin="67.6,379,0,0" VerticalAlignment="Top" Width="100" Uid="https://en.wikipedia.org/wiki/San_Francisco_Bay"/>

    </Grid>
</Window>


code for the image-HMUJ9320.JPG
<?xml version="1.0" encoding="utf-8" ?>
<configuration>
    <startup> 
        <supportedRuntime version="v4.0" sku=".NETFramework,Version=v4.7.2" />
    </startup>
</configuration>
