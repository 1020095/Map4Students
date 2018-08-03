# Map4Students
<Window x:Class="Map4Students.MainWindow"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:local="clr-namespace:Map4Students"
        mc:Ignorable="d"
        Title="MainWindow" Height="1150" Width="1500">
    <Grid>
        <Grid.RowDefinitions>
            <RowDefinition Height="77.5"/>
            <RowDefinition Height="22.5"/>
            <RowDefinition Height="100"/>
            <RowDefinition Height="100"/>
            <RowDefinition Height="100"/>
            <RowDefinition Height="100"/>
            <RowDefinition Height="100"/>
            <RowDefinition Height="100"/>
            <RowDefinition Height="100"/>
            <RowDefinition Height="100"/>
            <RowDefinition Height="100"/>
            <RowDefinition Height="100"/>
        </Grid.RowDefinitions>
        <Grid.ColumnDefinitions>
            <ColumnDefinition Width="100">
            </ColumnDefinition>
            <ColumnDefinition Width="100">
            </ColumnDefinition>
            <ColumnDefinition Width="100">
            </ColumnDefinition>
            <ColumnDefinition Width="100">
            </ColumnDefinition>
            <ColumnDefinition Width="100">
            </ColumnDefinition>
            <ColumnDefinition Width="100">
            </ColumnDefinition>
            <ColumnDefinition Width="100">
            </ColumnDefinition>
            <ColumnDefinition Width="100">
            </ColumnDefinition>
            <ColumnDefinition Width="100">
            </ColumnDefinition>
            <ColumnDefinition Width="100">
            </ColumnDefinition>
            <ColumnDefinition Width="100">
            </ColumnDefinition>
            <ColumnDefinition Width="100">
            </ColumnDefinition>
            <ColumnDefinition Width="100">
            </ColumnDefinition>
            <ColumnDefinition Width="100">
            </ColumnDefinition>
            <ColumnDefinition Width="100">
            </ColumnDefinition>
        </Grid.ColumnDefinitions>

        <!--Column 1: Shows period timing and number-->
        <TextBlock HorizontalAlignment="Center" Grid.Row="1" Grid.Column="1">Days</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Row="2" VerticalAlignment="Center" Grid.Column="1">Tutorial</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Row="2" VerticalAlignment="Bottom" Margin="0,0,0,20" Opacity="0.5" Grid.Column="1">(8:25am - 8:50am)</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Row="3" VerticalAlignment="Center" Grid.Column="1">Period 1</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Row="3" VerticalAlignment="Bottom" Margin="0,0,0,20" Opacity="0.5" Grid.Column="1">(8:50am - 9:45am)</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Row="4" VerticalAlignment="Center" Grid.Column="1">Period 2</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Row="4" VerticalAlignment="Bottom" Margin="0,0,0,20" Opacity="0.5" Grid.Column="1">(9:50am - 10:45am)</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Row="5" VerticalAlignment="Center" Grid.Column="1">Period 3</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Row="5" VerticalAlignment="Bottom" Margin="0,0,0,20" Opacity="0.5" Grid.Column="1">(11:00am - 11:50am)</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Row="6" VerticalAlignment="Center" Grid.Column="1">Period 4</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Row="6" VerticalAlignment="Bottom" Margin="0,0,0,20" Opacity="0.5" Grid.Column="1">(11:55am - 12:45pm)</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Row="7" VerticalAlignment="Center" Grid.Column="1">Period 5</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Row="7" VerticalAlignment="Bottom" Margin="0,0,0,20" Opacity="0.5" Grid.Column="1">(1:25pm - 2:15pm)</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Row="8" VerticalAlignment="Center" Grid.Column="1">Period 6</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Row="8" VerticalAlignment="Bottom" Margin="0,0,0,20" Opacity="0.5" Grid.Column="1">(2:20pm - 3:05pm)</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Row="9" VerticalAlignment="Center" Grid.Column="1">After-school Sport</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Row="9" VerticalAlignment="Bottom" Margin="0,0,0,20" Opacity="0.5" Grid.Column="1">(3:05pm - 4:30pm)</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Row="10" VerticalAlignment="Center" Grid.Column="1">After-school Sport</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Row="10" VerticalAlignment="Bottom" Margin="1,0,1,19.5" Opacity="0.5" Grid.Column="1">(4:30pm - 5:30pm)</TextBlock>

        <!--Row 1: Shows day of the week-->
        <TextBlock HorizontalAlignment="Center" Grid.Column="2" Grid.Row="1">Monday</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Column="3" Grid.Row="1">Tuesday</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Column="4" Grid.Row="1">Wednesday</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Column="5" Grid.Row="1">Thursday</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Column="6" Grid.Row="1">Friday</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Column="7" Grid.Row="1">Saturday</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Column="8" Grid.Row="1">Monday</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Column="9" Grid.Row="1">Tuesday</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Column="10" Grid.Row="1">Wednesday</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Column="11" Grid.Row="1">Thursday</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Column="12" Grid.Row="1">Friday</TextBlock>
        <TextBlock HorizontalAlignment="Center" Grid.Column="13" Grid.Row="1">Saturday</TextBlock>

        <!--Buttons for different periods-->
        <Button Grid.Column="2" Grid.Row="2" >
            <TextBlock HorizontalAlignment="Center" VerticalAlignment="Center"><Run Text="M-KSL Tutorial"/><LineBreak/><Run Text="      Mr Lim"/></TextBlock>
        </Button>
        <Button Grid.Column="3" Grid.Row="2" >
            <TextBlock HorizontalAlignment="Center" VerticalAlignment="Center"><Run Text="M-KSL Tutorial"/><LineBreak/><Run Text="      Mr Lim"/></TextBlock>
        </Button>
        <Button Grid.Column="4" Grid.Row="2" >
            <TextBlock HorizontalAlignment="Center" VerticalAlignment="Center"><Run Text="M-KSL Tutorial"/><LineBreak/><Run Text="      Mr Lim"/></TextBlock>
        </Button>
        <Button Grid.Column="5" Grid.Row="2" >
            <TextBlock HorizontalAlignment="Center" VerticalAlignment="Center"><Run Text="M-KSL Tutorial"/><LineBreak/><Run Text="      Mr Lim"/></TextBlock>
        </Button>
        <Button Grid.Column="6" Grid.Row="2" >
            <TextBlock HorizontalAlignment="Center" VerticalAlignment="Center"><Run Text="M-KSL Tutorial"/><LineBreak/><Run Text="      Mr Lim"/></TextBlock>
        </Button>
        <Button Grid.Column="8" Grid.Row="2" >
            <TextBlock HorizontalAlignment="Center" VerticalAlignment="Center"><Run Text="M-KSL Tutorial"/><LineBreak/><Run Text="      Mr Lim"/></TextBlock>
        </Button>
        <Button Grid.Column="9" Grid.Row="2" >
            <TextBlock HorizontalAlignment="Center" VerticalAlignment="Center"><Run Text="M-KSL Tutorial"/><LineBreak/><Run Text="      Mr Lim"/></TextBlock>
        </Button>
        <Button Grid.Column="10" Grid.Row="2" >
            <TextBlock HorizontalAlignment="Center" VerticalAlignment="Center"><Run Text="M-KSL Tutorial"/><LineBreak/><Run Text="      Mr Lim"/></TextBlock>
        </Button>
        <Button Grid.Column="11" Grid.Row="2" >
            <TextBlock HorizontalAlignment="Center" VerticalAlignment="Center"><Run Text="M-KSL Tutorial"/><LineBreak/><Run Text="      Mr Lim"/></TextBlock>
        </Button>
        <Button Grid.Column="12" Grid.Row="2" >
            <TextBlock HorizontalAlignment="Center" VerticalAlignment="Center"><Run Text="M-KSL Tutorial"/><LineBreak/><Run Text="      Mr Lim"/></TextBlock>
        </Button>
        <Button Grid.Column="13" Grid.Row="2" >
            <TextBlock HorizontalAlignment="Center" VerticalAlignment="Center"><Run Text="M-KSL Tutorial"/><LineBreak/><Run Text="      Mr Lim"/></TextBlock>
        </Button>
        
        
    </Grid>
</Window>
