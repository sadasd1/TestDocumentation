<a name='assembly'></a>
# NTL.Examples

## Contents

- [App](#T-NTL-Examples-App 'NTL.Examples.App')
  - [InitializeComponent()](#M-NTL-Examples-App-InitializeComponent 'NTL.Examples.App.InitializeComponent')
  - [Main()](#M-NTL-Examples-App-Main 'NTL.Examples.App.Main')
- [ArrayToStringConverter](#T-NTL-GUI-Converters-ArrayToStringConverter 'NTL.GUI.Converters.ArrayToStringConverter')
  - [Convert(value,targetType,parameter,culture)](#M-NTL-GUI-Converters-ArrayToStringConverter-Convert-System-Object,System-Type,System-Object,System-Globalization-CultureInfo- 'NTL.GUI.Converters.ArrayToStringConverter.Convert(System.Object,System.Type,System.Object,System.Globalization.CultureInfo)')
  - [ConvertBack(value,targetType,parameter,culture)](#M-NTL-GUI-Converters-ArrayToStringConverter-ConvertBack-System-Object,System-Type,System-Object,System-Globalization-CultureInfo- 'NTL.GUI.Converters.ArrayToStringConverter.ConvertBack(System.Object,System.Type,System.Object,System.Globalization.CultureInfo)')
- [BaseTestViewModel](#T-NTL-GUI-ViewModels-BaseTestViewModel 'NTL.GUI.ViewModels.BaseTestViewModel')
  - [canRunTest](#F-NTL-GUI-ViewModels-BaseTestViewModel-canRunTest 'NTL.GUI.ViewModels.BaseTestViewModel.canRunTest')
  - [name](#F-NTL-GUI-ViewModels-BaseTestViewModel-name 'NTL.GUI.ViewModels.BaseTestViewModel.name')
  - [target](#F-NTL-GUI-ViewModels-BaseTestViewModel-target 'NTL.GUI.ViewModels.BaseTestViewModel.target')
  - [CanRunTest](#P-NTL-GUI-ViewModels-BaseTestViewModel-CanRunTest 'NTL.GUI.ViewModels.BaseTestViewModel.CanRunTest')
  - [IsTestRunning](#P-NTL-GUI-ViewModels-BaseTestViewModel-IsTestRunning 'NTL.GUI.ViewModels.BaseTestViewModel.IsTestRunning')
  - [LocalHandler](#P-NTL-GUI-ViewModels-BaseTestViewModel-LocalHandler 'NTL.GUI.ViewModels.BaseTestViewModel.LocalHandler')
  - [Name](#P-NTL-GUI-ViewModels-BaseTestViewModel-Name 'NTL.GUI.ViewModels.BaseTestViewModel.Name')
  - [RunTest](#P-NTL-GUI-ViewModels-BaseTestViewModel-RunTest 'NTL.GUI.ViewModels.BaseTestViewModel.RunTest')
  - [Target](#P-NTL-GUI-ViewModels-BaseTestViewModel-Target 'NTL.GUI.ViewModels.BaseTestViewModel.Target')
  - [CanExecute(parameters)](#M-NTL-GUI-ViewModels-BaseTestViewModel-CanExecute-System-Object- 'NTL.GUI.ViewModels.BaseTestViewModel.CanExecute(System.Object)')
  - [Execute(parameters)](#M-NTL-GUI-ViewModels-BaseTestViewModel-Execute-System-Object- 'NTL.GUI.ViewModels.BaseTestViewModel.Execute(System.Object)')
- [BaseViewModel](#T-NTL-GUI-ViewModels-BaseViewModel 'NTL.GUI.ViewModels.BaseViewModel')
  - [OnPropertyChanged(propertyName)](#M-NTL-GUI-ViewModels-BaseViewModel-OnPropertyChanged-System-String- 'NTL.GUI.ViewModels.BaseViewModel.OnPropertyChanged(System.String)')
- [CycleDesigner](#T-NTL-GUI-CycleDesigner 'NTL.GUI.CycleDesigner')
  - [InitializeComponent()](#M-NTL-GUI-CycleDesigner-InitializeComponent 'NTL.GUI.CycleDesigner.InitializeComponent')
- [CycleSelectionView](#T-NTL-GUI-CycleSelectionView 'NTL.GUI.CycleSelectionView')
  - [InitializeComponent()](#M-NTL-GUI-CycleSelectionView-InitializeComponent 'NTL.GUI.CycleSelectionView.InitializeComponent')
- [EnumBaseViewModel](#T-NTL-GUI-ViewModels-EnumBaseViewModel 'NTL.GUI.ViewModels.EnumBaseViewModel')
  - [itemsSource](#F-NTL-GUI-ViewModels-EnumBaseViewModel-itemsSource 'NTL.GUI.ViewModels.EnumBaseViewModel.itemsSource')
  - [ItemsSource](#P-NTL-GUI-ViewModels-EnumBaseViewModel-ItemsSource 'NTL.GUI.ViewModels.EnumBaseViewModel.ItemsSource')
- [GenerateHeartBeatView](#T-NTL-GUI-GenerateHeartBeatView 'NTL.GUI.GenerateHeartBeatView')
  - [InitializeComponent()](#M-NTL-GUI-GenerateHeartBeatView-InitializeComponent 'NTL.GUI.GenerateHeartBeatView.InitializeComponent')
- [GenerateHeartBeatViewModel](#T-NTL-GUI-ViewModels-GenerateHeartBeatViewModel 'NTL.GUI.ViewModels.GenerateHeartBeatViewModel')
  - [ActionLabel](#P-NTL-GUI-ViewModels-GenerateHeartBeatViewModel-ActionLabel 'NTL.GUI.ViewModels.GenerateHeartBeatViewModel.ActionLabel')
  - [Period](#P-NTL-GUI-ViewModels-GenerateHeartBeatViewModel-Period 'NTL.GUI.ViewModels.GenerateHeartBeatViewModel.Period')
  - [Execute(parameters)](#M-NTL-GUI-ViewModels-GenerateHeartBeatViewModel-Execute-System-Object- 'NTL.GUI.ViewModels.GenerateHeartBeatViewModel.Execute(System.Object)')
- [GenericBaseViewModel](#T-NTL-GUI-ViewModels-GenericBaseViewModel 'NTL.GUI.ViewModels.GenericBaseViewModel')
  - [inputs](#F-NTL-GUI-ViewModels-GenericBaseViewModel-inputs 'NTL.GUI.ViewModels.GenericBaseViewModel.inputs')
  - [outputs](#F-NTL-GUI-ViewModels-GenericBaseViewModel-outputs 'NTL.GUI.ViewModels.GenericBaseViewModel.outputs')
  - [Inputs](#P-NTL-GUI-ViewModels-GenericBaseViewModel-Inputs 'NTL.GUI.ViewModels.GenericBaseViewModel.Inputs')
  - [Outputs](#P-NTL-GUI-ViewModels-GenericBaseViewModel-Outputs 'NTL.GUI.ViewModels.GenericBaseViewModel.Outputs')
  - [Execute(parameters)](#M-NTL-GUI-ViewModels-GenericBaseViewModel-Execute-System-Object- 'NTL.GUI.ViewModels.GenericBaseViewModel.Execute(System.Object)')
- [GetLoadDataResultViewModel](#T-NTL-GUI-ViewModels-GetLoadDataResultViewModel 'NTL.GUI.ViewModels.GetLoadDataResultViewModel')
  - [Data](#P-NTL-GUI-ViewModels-GetLoadDataResultViewModel-Data 'NTL.GUI.ViewModels.GetLoadDataResultViewModel.Data')
  - [DataSize](#P-NTL-GUI-ViewModels-GetLoadDataResultViewModel-DataSize 'NTL.GUI.ViewModels.GetLoadDataResultViewModel.DataSize')
  - [RequestResult](#P-NTL-GUI-ViewModels-GetLoadDataResultViewModel-RequestResult 'NTL.GUI.ViewModels.GetLoadDataResultViewModel.RequestResult')
- [GetMCIErrorResultView](#T-NTL-GUI-GetMCIErrorResultView 'NTL.GUI.GetMCIErrorResultView')
  - [InitializeComponent()](#M-NTL-GUI-GetMCIErrorResultView-InitializeComponent 'NTL.GUI.GetMCIErrorResultView.InitializeComponent')
- [GetMCIErrorResultsViewModel](#T-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel')
  - [motorIndex](#F-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-motorIndex 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.motorIndex')
  - [ClassBForcedToStop](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-ClassBForcedToStop 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.ClassBForcedToStop')
  - [CurrentSensorField](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-CurrentSensorField 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.CurrentSensorField')
  - [DCBusOutOfRange](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-DCBusOutOfRange 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.DCBusOutOfRange')
  - [DCBusOverVoltage](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-DCBusOverVoltage 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.DCBusOverVoltage')
  - [DCBusUnderVoltage](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-DCBusUnderVoltage 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.DCBusUnderVoltage')
  - [HWOverCurrent](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-HWOverCurrent 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.HWOverCurrent')
  - [InitializationFailed](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-InitializationFailed 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.InitializationFailed')
  - [InputCapturePlausibilityMaxFailed](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-InputCapturePlausibilityMaxFailed 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.InputCapturePlausibilityMaxFailed')
  - [InputCapturePlausibilityMinFailed](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-InputCapturePlausibilityMinFailed 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.InputCapturePlausibilityMinFailed')
  - [InterruptDisabled](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-InterruptDisabled 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.InterruptDisabled')
  - [InverterOverTemp](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-InverterOverTemp 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.InverterOverTemp')
  - [LockedRotorAtStartup](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-LockedRotorAtStartup 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.LockedRotorAtStartup')
  - [LockedRotorInRunning](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-LockedRotorInRunning 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.LockedRotorInRunning')
  - [MCIErrorFound](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-MCIErrorFound 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.MCIErrorFound')
  - [MotorIndexInput](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-MotorIndexInput 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.MotorIndexInput')
  - [MotorOverheating](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-MotorOverheating 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.MotorOverheating')
  - [ObserverFailure](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-ObserverFailure 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.ObserverFailure')
  - [PhaseLost](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-PhaseLost 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.PhaseLost')
  - [RequestResult](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-RequestResult 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.RequestResult')
  - [SWOverCurrent](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-SWOverCurrent 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.SWOverCurrent')
  - [ShutdownHardwareFailed](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-ShutdownHardwareFailed 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.ShutdownHardwareFailed')
  - [SpeedCheckFailed](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-SpeedCheckFailed 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.SpeedCheckFailed')
  - [StratorOverTemp](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-StratorOverTemp 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.StratorOverTemp')
  - [VoltageSensorField](#P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-VoltageSensorField 'NTL.GUI.ViewModels.GetMCIErrorResultsViewModel.VoltageSensorField')
- [GetMaxPackageSizeResultView](#T-NTL-GUI-GetMaxPackageSizeResultView 'NTL.GUI.GetMaxPackageSizeResultView')
  - [InitializeComponent()](#M-NTL-GUI-GetMaxPackageSizeResultView-InitializeComponent 'NTL.GUI.GetMaxPackageSizeResultView.InitializeComponent')
- [GetMaxPackageSizeResultViewModel](#T-NTL-GUI-ViewModels-GetMaxPackageSizeResultViewModel 'NTL.GUI.ViewModels.GetMaxPackageSizeResultViewModel')
  - [ReceiveMaxPackageSize](#P-NTL-GUI-ViewModels-GetMaxPackageSizeResultViewModel-ReceiveMaxPackageSize 'NTL.GUI.ViewModels.GetMaxPackageSizeResultViewModel.ReceiveMaxPackageSize')
  - [RequestResult](#P-NTL-GUI-ViewModels-GetMaxPackageSizeResultViewModel-RequestResult 'NTL.GUI.ViewModels.GetMaxPackageSizeResultViewModel.RequestResult')
  - [SendMaxPackageSize](#P-NTL-GUI-ViewModels-GetMaxPackageSizeResultViewModel-SendMaxPackageSize 'NTL.GUI.ViewModels.GetMaxPackageSizeResultViewModel.SendMaxPackageSize')
- [GetMotorFVTResultView](#T-NTL-GUI-GetMotorFVTResultView 'NTL.GUI.GetMotorFVTResultView')
  - [InitializeComponent()](#M-NTL-GUI-GetMotorFVTResultView-InitializeComponent 'NTL.GUI.GetMotorFVTResultView.InitializeComponent')
- [GetMotorFVTResultViewModel](#T-NTL-GUI-ViewModels-GetMotorFVTResultViewModel 'NTL.GUI.ViewModels.GetMotorFVTResultViewModel')
  - [CircuitOC](#P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-CircuitOC 'NTL.GUI.ViewModels.GetMotorFVTResultViewModel.CircuitOC')
  - [DCBus](#P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-DCBus 'NTL.GUI.ViewModels.GetMotorFVTResultViewModel.DCBus')
  - [DCBusVoltageClosed](#P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-DCBusVoltageClosed 'NTL.GUI.ViewModels.GetMotorFVTResultViewModel.DCBusVoltageClosed')
  - [DCBusVoltageOpen](#P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-DCBusVoltageOpen 'NTL.GUI.ViewModels.GetMotorFVTResultViewModel.DCBusVoltageOpen')
  - [ExpiredData](#P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-ExpiredData 'NTL.GUI.ViewModels.GetMotorFVTResultViewModel.ExpiredData')
  - [InvalidDataRead](#P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-InvalidDataRead 'NTL.GUI.ViewModels.GetMotorFVTResultViewModel.InvalidDataRead')
  - [MotorIndex](#P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-MotorIndex 'NTL.GUI.ViewModels.GetMotorFVTResultViewModel.MotorIndex')
  - [OC](#P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-OC 'NTL.GUI.ViewModels.GetMotorFVTResultViewModel.OC')
  - [PhaseCurrentA](#P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-PhaseCurrentA 'NTL.GUI.ViewModels.GetMotorFVTResultViewModel.PhaseCurrentA')
  - [PhaseCurrentB](#P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-PhaseCurrentB 'NTL.GUI.ViewModels.GetMotorFVTResultViewModel.PhaseCurrentB')
  - [PhaseCurrentC](#P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-PhaseCurrentC 'NTL.GUI.ViewModels.GetMotorFVTResultViewModel.PhaseCurrentC')
  - [PhaseVoltageA](#P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-PhaseVoltageA 'NTL.GUI.ViewModels.GetMotorFVTResultViewModel.PhaseVoltageA')
  - [PhaseVoltageB](#P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-PhaseVoltageB 'NTL.GUI.ViewModels.GetMotorFVTResultViewModel.PhaseVoltageB')
  - [PhaseVoltageC](#P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-PhaseVoltageC 'NTL.GUI.ViewModels.GetMotorFVTResultViewModel.PhaseVoltageC')
  - [RequestResult](#P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-RequestResult 'NTL.GUI.ViewModels.GetMotorFVTResultViewModel.RequestResult')
  - [TimedOut](#P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-TimedOut 'NTL.GUI.ViewModels.GetMotorFVTResultViewModel.TimedOut')
- [InputBaseView](#T-NTL-GUI-Views-InputBaseView 'NTL.GUI.Views.InputBaseView')
  - [InitializeComponent()](#M-NTL-GUI-Views-InputBaseView-InitializeComponent 'NTL.GUI.Views.InputBaseView.InitializeComponent')
- [InputBaseViewModel](#T-NTL-GUI-ViewModels-InputBaseViewModel 'NTL.GUI.ViewModels.InputBaseViewModel')
  - [name](#F-NTL-GUI-ViewModels-InputBaseViewModel-name 'NTL.GUI.ViewModels.InputBaseViewModel.name')
  - [value](#F-NTL-GUI-ViewModels-InputBaseViewModel-value 'NTL.GUI.ViewModels.InputBaseViewModel.value')
  - [Name](#P-NTL-GUI-ViewModels-InputBaseViewModel-Name 'NTL.GUI.ViewModels.InputBaseViewModel.Name')
  - [Value](#P-NTL-GUI-ViewModels-InputBaseViewModel-Value 'NTL.GUI.ViewModels.InputBaseViewModel.Value')
- [MainWindow](#T-NTL-GUI-MainWindow 'NTL.GUI.MainWindow')
  - [InitializeComponent()](#M-NTL-GUI-MainWindow-InitializeComponent 'NTL.GUI.MainWindow.InitializeComponent')
- [NTLTestModel](#T-NTL-GUI-NTLTestModel 'NTL.GUI.NTLTestModel')
  - [StartFVTVM](#P-NTL-GUI-NTLTestModel-StartFVTVM 'NTL.GUI.NTLTestModel.StartFVTVM')
- [NucleusHandlerViewModel](#T-NTL-GUI-ViewModels-NucleusHandlerViewModel 'NTL.GUI.ViewModels.NucleusHandlerViewModel')
  - [#ctor()](#M-NTL-GUI-ViewModels-NucleusHandlerViewModel-#ctor 'NTL.GUI.ViewModels.NucleusHandlerViewModel.#ctor')
  - [ntlViewModels](#F-NTL-GUI-ViewModels-NucleusHandlerViewModel-ntlViewModels 'NTL.GUI.ViewModels.NucleusHandlerViewModel.ntlViewModels')
  - [receivedMessaged](#F-NTL-GUI-ViewModels-NucleusHandlerViewModel-receivedMessaged 'NTL.GUI.ViewModels.NucleusHandlerViewModel.receivedMessaged')
  - [Add](#P-NTL-GUI-ViewModels-NucleusHandlerViewModel-Add 'NTL.GUI.ViewModels.NucleusHandlerViewModel.Add')
  - [ClearMessages](#P-NTL-GUI-ViewModels-NucleusHandlerViewModel-ClearMessages 'NTL.GUI.ViewModels.NucleusHandlerViewModel.ClearMessages')
  - [MethodToAdd](#P-NTL-GUI-ViewModels-NucleusHandlerViewModel-MethodToAdd 'NTL.GUI.ViewModels.NucleusHandlerViewModel.MethodToAdd')
  - [MethodToRemove](#P-NTL-GUI-ViewModels-NucleusHandlerViewModel-MethodToRemove 'NTL.GUI.ViewModels.NucleusHandlerViewModel.MethodToRemove')
  - [NTLViewModels](#P-NTL-GUI-ViewModels-NucleusHandlerViewModel-NTLViewModels 'NTL.GUI.ViewModels.NucleusHandlerViewModel.NTLViewModels')
  - [NucleusHandlerMethods](#P-NTL-GUI-ViewModels-NucleusHandlerViewModel-NucleusHandlerMethods 'NTL.GUI.ViewModels.NucleusHandlerViewModel.NucleusHandlerMethods')
  - [NucleusHandlerMethodsView](#P-NTL-GUI-ViewModels-NucleusHandlerViewModel-NucleusHandlerMethodsView 'NTL.GUI.ViewModels.NucleusHandlerViewModel.NucleusHandlerMethodsView')
  - [ReceivedMessages](#P-NTL-GUI-ViewModels-NucleusHandlerViewModel-ReceivedMessages 'NTL.GUI.ViewModels.NucleusHandlerViewModel.ReceivedMessages')
  - [Remove](#P-NTL-GUI-ViewModels-NucleusHandlerViewModel-Remove 'NTL.GUI.ViewModels.NucleusHandlerViewModel.Remove')
  - [SearchFilter](#P-NTL-GUI-ViewModels-NucleusHandlerViewModel-SearchFilter 'NTL.GUI.ViewModels.NucleusHandlerViewModel.SearchFilter')
  - [WiredBoxVM](#P-NTL-GUI-ViewModels-NucleusHandlerViewModel-WiredBoxVM 'NTL.GUI.ViewModels.NucleusHandlerViewModel.WiredBoxVM')
  - [AddViewModel(viewModel)](#M-NTL-GUI-ViewModels-NucleusHandlerViewModel-AddViewModel-NTL-GUI-ViewModels-BaseTestViewModel- 'NTL.GUI.ViewModels.NucleusHandlerViewModel.AddViewModel(NTL.GUI.ViewModels.BaseTestViewModel)')
  - [AddViewModel(taskName)](#M-NTL-GUI-ViewModels-NucleusHandlerViewModel-AddViewModel-System-String- 'NTL.GUI.ViewModels.NucleusHandlerViewModel.AddViewModel(System.String)')
  - [GetMatchViewModel(taskName)](#M-NTL-GUI-ViewModels-NucleusHandlerViewModel-GetMatchViewModel-System-String- 'NTL.GUI.ViewModels.NucleusHandlerViewModel.GetMatchViewModel(System.String)')
  - [GetTypesFromNamespace(assembly,desiredNamespace)](#M-NTL-GUI-ViewModels-NucleusHandlerViewModel-GetTypesFromNamespace-System-Reflection-Assembly,System-String- 'NTL.GUI.ViewModels.NucleusHandlerViewModel.GetTypesFromNamespace(System.Reflection.Assembly,System.String)')
  - [WiredBoxVM_OpenPortExecuted(sender,e)](#M-NTL-GUI-ViewModels-NucleusHandlerViewModel-WiredBoxVM_OpenPortExecuted-System-Object,System-EventArgs- 'NTL.GUI.ViewModels.NucleusHandlerViewModel.WiredBoxVM_OpenPortExecuted(System.Object,System.EventArgs)')
- [OutputBaseView](#T-NTL-GUI-Views-OutputBaseView 'NTL.GUI.Views.OutputBaseView')
  - [InitializeComponent()](#M-NTL-GUI-Views-OutputBaseView-InitializeComponent 'NTL.GUI.Views.OutputBaseView.InitializeComponent')
- [OutputBaseViewModel](#T-NTL-GUI-ViewModels-OutputBaseViewModel 'NTL.GUI.ViewModels.OutputBaseViewModel')
  - [name](#F-NTL-GUI-ViewModels-OutputBaseViewModel-name 'NTL.GUI.ViewModels.OutputBaseViewModel.name')
  - [value](#F-NTL-GUI-ViewModels-OutputBaseViewModel-value 'NTL.GUI.ViewModels.OutputBaseViewModel.value')
  - [Name](#P-NTL-GUI-ViewModels-OutputBaseViewModel-Name 'NTL.GUI.ViewModels.OutputBaseViewModel.Name')
  - [Value](#P-NTL-GUI-ViewModels-OutputBaseViewModel-Value 'NTL.GUI.ViewModels.OutputBaseViewModel.Value')
- [PCcontrolView](#T-NTL-GUI-PCcontrolView 'NTL.GUI.PCcontrolView')
  - [InitializeComponent()](#M-NTL-GUI-PCcontrolView-InitializeComponent 'NTL.GUI.PCcontrolView.InitializeComponent')
- [PCcontrolViewModel](#T-NTL-GUI-ViewModels-PCcontrolViewModel 'NTL.GUI.ViewModels.PCcontrolViewModel')
  - [RequestResult](#P-NTL-GUI-ViewModels-PCcontrolViewModel-RequestResult 'NTL.GUI.ViewModels.PCcontrolViewModel.RequestResult')
  - [Execute(parameters)](#M-NTL-GUI-ViewModels-PCcontrolViewModel-Execute-System-Object- 'NTL.GUI.ViewModels.PCcontrolViewModel.Execute(System.Object)')
- [ParallelProgrammingExample](#T-NTL-GUI-ParallelProgrammingExample 'NTL.GUI.ParallelProgrammingExample')
  - [InitializeComponent()](#M-NTL-GUI-ParallelProgrammingExample-InitializeComponent 'NTL.GUI.ParallelProgrammingExample.InitializeComponent')
- [PublishRegulationsResultView](#T-NTL-GUI-PublishRegulationsResultView 'NTL.GUI.PublishRegulationsResultView')
  - [InitializeComponent()](#M-NTL-GUI-PublishRegulationsResultView-InitializeComponent 'NTL.GUI.PublishRegulationsResultView.InitializeComponent')
- [PublishRegulationsViewModel](#T-NTL-GUI-ViewModels-PublishRegulationsViewModel 'NTL.GUI.ViewModels.PublishRegulationsViewModel')
  - [RequestResult](#P-NTL-GUI-ViewModels-PublishRegulationsViewModel-RequestResult 'NTL.GUI.ViewModels.PublishRegulationsViewModel.RequestResult')
- [RegulationsView](#T-NTL-GUI-RegulationsView 'NTL.GUI.RegulationsView')
  - [InitializeComponent()](#M-NTL-GUI-RegulationsView-InitializeComponent 'NTL.GUI.RegulationsView.InitializeComponent')
- [RegulationsViewModel](#T-NTL-GUI-ViewModels-RegulationsViewModel 'NTL.GUI.ViewModels.RegulationsViewModel')
  - [regulations](#F-NTL-GUI-ViewModels-RegulationsViewModel-regulations 'NTL.GUI.ViewModels.RegulationsViewModel.regulations')
- [RelayCommand](#T-NTL-GUI-RelayCommand 'NTL.GUI.RelayCommand')
  - [#ctor(execute,canExecute)](#M-NTL-GUI-RelayCommand-#ctor-System-Action{System-Object},System-Func{System-Object,System-Boolean}- 'NTL.GUI.RelayCommand.#ctor(System.Action{System.Object},System.Func{System.Object,System.Boolean})')
  - [canExecute](#F-NTL-GUI-RelayCommand-canExecute 'NTL.GUI.RelayCommand.canExecute')
  - [execute](#F-NTL-GUI-RelayCommand-execute 'NTL.GUI.RelayCommand.execute')
  - [CanExecute(parameter)](#M-NTL-GUI-RelayCommand-CanExecute-System-Object- 'NTL.GUI.RelayCommand.CanExecute(System.Object)')
  - [Execute(parameter)](#M-NTL-GUI-RelayCommand-Execute-System-Object- 'NTL.GUI.RelayCommand.Execute(System.Object)')
  - [OnCanExecuteChanged()](#M-NTL-GUI-RelayCommand-OnCanExecuteChanged 'NTL.GUI.RelayCommand.OnCanExecuteChanged')
- [Resources](#T-NTL-Examples-Properties-Resources 'NTL.Examples.Properties.Resources')
  - [Culture](#P-NTL-Examples-Properties-Resources-Culture 'NTL.Examples.Properties.Resources.Culture')
  - [ResourceManager](#P-NTL-Examples-Properties-Resources-ResourceManager 'NTL.Examples.Properties.Resources.ResourceManager')
- [RevealHandlerExample](#T-NTL-GUI-RevealHandlerExample 'NTL.GUI.RevealHandlerExample')
  - [InitializeComponent()](#M-NTL-GUI-RevealHandlerExample-InitializeComponent 'NTL.GUI.RevealHandlerExample.InitializeComponent')
- [SetLoadDataView](#T-NTL-GUI-SetLoadDataView 'NTL.GUI.SetLoadDataView')
  - [InitializeComponent()](#M-NTL-GUI-SetLoadDataView-InitializeComponent 'NTL.GUI.SetLoadDataView.InitializeComponent')
- [SetLoadDataViewModel](#T-NTL-GUI-ViewModels-SetLoadDataViewModel 'NTL.GUI.ViewModels.SetLoadDataViewModel')
  - [Data](#P-NTL-GUI-ViewModels-SetLoadDataViewModel-Data 'NTL.GUI.ViewModels.SetLoadDataViewModel.Data')
  - [DataSize](#P-NTL-GUI-ViewModels-SetLoadDataViewModel-DataSize 'NTL.GUI.ViewModels.SetLoadDataViewModel.DataSize')
  - [DataSizeVisibility](#P-NTL-GUI-ViewModels-SetLoadDataViewModel-DataSizeVisibility 'NTL.GUI.ViewModels.SetLoadDataViewModel.DataSizeVisibility')
  - [DataVisibility](#P-NTL-GUI-ViewModels-SetLoadDataViewModel-DataVisibility 'NTL.GUI.ViewModels.SetLoadDataViewModel.DataVisibility')
  - [LoadIdVisibility](#P-NTL-GUI-ViewModels-SetLoadDataViewModel-LoadIdVisibility 'NTL.GUI.ViewModels.SetLoadDataViewModel.LoadIdVisibility')
  - [RequestResult](#P-NTL-GUI-ViewModels-SetLoadDataViewModel-RequestResult 'NTL.GUI.ViewModels.SetLoadDataViewModel.RequestResult')
  - [Execute(parameters)](#M-NTL-GUI-ViewModels-SetLoadDataViewModel-Execute-System-Object- 'NTL.GUI.ViewModels.SetLoadDataViewModel.Execute(System.Object)')
- [SettingFileDownloadView](#T-NTL-GUI-Views-SettingFileDownloadView 'NTL.GUI.Views.SettingFileDownloadView')
  - [InitializeComponent()](#M-NTL-GUI-Views-SettingFileDownloadView-InitializeComponent 'NTL.GUI.Views.SettingFileDownloadView.InitializeComponent')
- [SettingFileDownloadViewModel](#T-NTL-GUI-ViewModels-SettingFileDownloadViewModel 'NTL.GUI.ViewModels.SettingFileDownloadViewModel')
  - [SettingFilePath](#P-NTL-GUI-ViewModels-SettingFileDownloadViewModel-SettingFilePath 'NTL.GUI.ViewModels.SettingFileDownloadViewModel.SettingFilePath')
- [SimpleTaskmanager](#T-GetLoadTest-SimpleTaskmanager 'GetLoadTest.SimpleTaskmanager')
  - [InitializeComponent()](#M-GetLoadTest-SimpleTaskmanager-InitializeComponent 'GetLoadTest.SimpleTaskmanager.InitializeComponent')
- [StartAndGetMotorFVTResultView](#T-NTL-GUI-StartAndGetMotorFVTResultView 'NTL.GUI.StartAndGetMotorFVTResultView')
  - [InitializeComponent()](#M-NTL-GUI-StartAndGetMotorFVTResultView-InitializeComponent 'NTL.GUI.StartAndGetMotorFVTResultView.InitializeComponent')
- [StartAndGetMotorFVTResultViewModel](#T-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel 'NTL.GUI.ViewModels.StartAndGetMotorFVTResultViewModel')
  - [CircuitOC](#P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-CircuitOC 'NTL.GUI.ViewModels.StartAndGetMotorFVTResultViewModel.CircuitOC')
  - [DCBus](#P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-DCBus 'NTL.GUI.ViewModels.StartAndGetMotorFVTResultViewModel.DCBus')
  - [DCBusVoltageClosed](#P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-DCBusVoltageClosed 'NTL.GUI.ViewModels.StartAndGetMotorFVTResultViewModel.DCBusVoltageClosed')
  - [DCBusVoltageOpen](#P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-DCBusVoltageOpen 'NTL.GUI.ViewModels.StartAndGetMotorFVTResultViewModel.DCBusVoltageOpen')
  - [Error](#P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-Error 'NTL.GUI.ViewModels.StartAndGetMotorFVTResultViewModel.Error')
  - [ExpiredData](#P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-ExpiredData 'NTL.GUI.ViewModels.StartAndGetMotorFVTResultViewModel.ExpiredData')
  - [InvalidDataRead](#P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-InvalidDataRead 'NTL.GUI.ViewModels.StartAndGetMotorFVTResultViewModel.InvalidDataRead')
  - [MotorIndex](#P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-MotorIndex 'NTL.GUI.ViewModels.StartAndGetMotorFVTResultViewModel.MotorIndex')
  - [OC](#P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-OC 'NTL.GUI.ViewModels.StartAndGetMotorFVTResultViewModel.OC')
  - [PhaseCurrentA](#P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-PhaseCurrentA 'NTL.GUI.ViewModels.StartAndGetMotorFVTResultViewModel.PhaseCurrentA')
  - [PhaseCurrentB](#P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-PhaseCurrentB 'NTL.GUI.ViewModels.StartAndGetMotorFVTResultViewModel.PhaseCurrentB')
  - [PhaseCurrentC](#P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-PhaseCurrentC 'NTL.GUI.ViewModels.StartAndGetMotorFVTResultViewModel.PhaseCurrentC')
  - [PhaseVoltageA](#P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-PhaseVoltageA 'NTL.GUI.ViewModels.StartAndGetMotorFVTResultViewModel.PhaseVoltageA')
  - [PhaseVoltageB](#P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-PhaseVoltageB 'NTL.GUI.ViewModels.StartAndGetMotorFVTResultViewModel.PhaseVoltageB')
  - [PhaseVoltageC](#P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-PhaseVoltageC 'NTL.GUI.ViewModels.StartAndGetMotorFVTResultViewModel.PhaseVoltageC')
  - [RequestResult](#P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-RequestResult 'NTL.GUI.ViewModels.StartAndGetMotorFVTResultViewModel.RequestResult')
  - [TimedOut](#P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-TimedOut 'NTL.GUI.ViewModels.StartAndGetMotorFVTResultViewModel.TimedOut')
- [StartMotorFVTResultView](#T-GetLoadTest-StartMotorFVTResultView 'GetLoadTest.StartMotorFVTResultView')
- [StartMotorFVTResultView](#T-NTL-GUI-StartMotorFVTResultView 'NTL.GUI.StartMotorFVTResultView')
  - [InitializeComponent()](#M-GetLoadTest-StartMotorFVTResultView-InitializeComponent 'GetLoadTest.StartMotorFVTResultView.InitializeComponent')
  - [InitializeComponent()](#M-NTL-GUI-StartMotorFVTResultView-InitializeComponent 'NTL.GUI.StartMotorFVTResultView.InitializeComponent')
- [StartMotorFVTResultViewModel](#T-NTL-GUI-ViewModels-StartMotorFVTResultViewModel 'NTL.GUI.ViewModels.StartMotorFVTResultViewModel')
  - [Error](#P-NTL-GUI-ViewModels-StartMotorFVTResultViewModel-Error 'NTL.GUI.ViewModels.StartMotorFVTResultViewModel.Error')
  - [MotorIndex](#P-NTL-GUI-ViewModels-StartMotorFVTResultViewModel-MotorIndex 'NTL.GUI.ViewModels.StartMotorFVTResultViewModel.MotorIndex')
- [StopMotorFVTResultView](#T-NTL-GUI-StopMotorFVTResultView 'NTL.GUI.StopMotorFVTResultView')
  - [InitializeComponent()](#M-NTL-GUI-StopMotorFVTResultView-InitializeComponent 'NTL.GUI.StopMotorFVTResultView.InitializeComponent')
- [StopMotorFVTResultViewModel](#T-NTL-GUI-ViewModels-StopMotorFVTResultViewModel 'NTL.GUI.ViewModels.StopMotorFVTResultViewModel')
  - [Code](#P-NTL-GUI-ViewModels-StopMotorFVTResultViewModel-Code 'NTL.GUI.ViewModels.StopMotorFVTResultViewModel.Code')
  - [RequestResult](#P-NTL-GUI-ViewModels-StopMotorFVTResultViewModel-RequestResult 'NTL.GUI.ViewModels.StopMotorFVTResultViewModel.RequestResult')
- [Test](#T-NTL-Examples-JabilTest-Test 'NTL.Examples.JabilTest.Test')
  - [#ctor(varSapce,otherParameters)](#M-NTL-Examples-JabilTest-Test-#ctor-NTL-Examples-JabilTest-ScriptVariableSpace,System-Object- 'NTL.Examples.JabilTest.Test.#ctor(NTL.Examples.JabilTest.ScriptVariableSpace,System.Object)')
  - [VariableSpace](#P-NTL-Examples-JabilTest-Test-VariableSpace 'NTL.Examples.JabilTest.Test.VariableSpace')
- [UsingScriptProvider](#T-NTL-Examples-ScriptProvider-UsingScriptProvider 'NTL.Examples.ScriptProvider.UsingScriptProvider')
  - [RunNucleusMethod(methodName,paramValues)](#M-NTL-Examples-ScriptProvider-UsingScriptProvider-RunNucleusMethod-System-String,System-String[]- 'NTL.Examples.ScriptProvider.UsingScriptProvider.RunNucleusMethod(System.String,System.String[])')
  - [StartDevice(comPort,nodeAddress)](#M-NTL-Examples-ScriptProvider-UsingScriptProvider-StartDevice-System-String,System-Byte- 'NTL.Examples.ScriptProvider.UsingScriptProvider.StartDevice(System.String,System.Byte)')
  - [StopDevice()](#M-NTL-Examples-ScriptProvider-UsingScriptProvider-StopDevice 'NTL.Examples.ScriptProvider.UsingScriptProvider.StopDevice')
- [VariableStreamExample](#T-NTL-GUI-VariableStreamExample 'NTL.GUI.VariableStreamExample')
  - [InitializeComponent()](#M-NTL-GUI-VariableStreamExample-InitializeComponent 'NTL.GUI.VariableStreamExample.InitializeComponent')
- [Window1](#T-NTL-GUI-Window1 'NTL.GUI.Window1')
  - [InitializeComponent()](#M-NTL-GUI-Window1-InitializeComponent 'NTL.GUI.Window1.InitializeComponent')
- [Window2](#T-GetLoadTest-Window2 'GetLoadTest.Window2')
- [Window2](#T-NTL-GUI-Window2 'NTL.GUI.Window2')
  - [InitializeComponent()](#M-GetLoadTest-Window2-InitializeComponent 'GetLoadTest.Window2.InitializeComponent')
  - [InitializeComponent()](#M-NTL-GUI-Window2-InitializeComponent 'NTL.GUI.Window2.InitializeComponent')
- [WiredBoxView](#T-NTL-GUI-Views-WiredBoxView 'NTL.GUI.Views.WiredBoxView')
  - [InitializeComponent()](#M-NTL-GUI-Views-WiredBoxView-InitializeComponent 'NTL.GUI.Views.WiredBoxView.InitializeComponent')
- [WiredBoxViewModel](#T-NTL-GUI-ViewModels-WiredBoxViewModel 'NTL.GUI.ViewModels.WiredBoxViewModel')
  - [port](#F-NTL-GUI-ViewModels-WiredBoxViewModel-port 'NTL.GUI.ViewModels.WiredBoxViewModel.port')
  - [ports](#F-NTL-GUI-ViewModels-WiredBoxViewModel-ports 'NTL.GUI.ViewModels.WiredBoxViewModel.ports')
  - [Address](#P-NTL-GUI-ViewModels-WiredBoxViewModel-Address 'NTL.GUI.ViewModels.WiredBoxViewModel.Address')
  - [Error](#P-NTL-GUI-ViewModels-WiredBoxViewModel-Error 'NTL.GUI.ViewModels.WiredBoxViewModel.Error')
  - [LocalHandler](#P-NTL-GUI-ViewModels-WiredBoxViewModel-LocalHandler 'NTL.GUI.ViewModels.WiredBoxViewModel.LocalHandler')
  - [OpenPort](#P-NTL-GUI-ViewModels-WiredBoxViewModel-OpenPort 'NTL.GUI.ViewModels.WiredBoxViewModel.OpenPort')
  - [Port](#P-NTL-GUI-ViewModels-WiredBoxViewModel-Port 'NTL.GUI.ViewModels.WiredBoxViewModel.Port')
  - [PortStatusAction](#P-NTL-GUI-ViewModels-WiredBoxViewModel-PortStatusAction 'NTL.GUI.ViewModels.WiredBoxViewModel.PortStatusAction')
  - [Ports](#P-NTL-GUI-ViewModels-WiredBoxViewModel-Ports 'NTL.GUI.ViewModels.WiredBoxViewModel.Ports')
  - [Protocol](#P-NTL-GUI-ViewModels-WiredBoxViewModel-Protocol 'NTL.GUI.ViewModels.WiredBoxViewModel.Protocol')
  - [Protocols](#P-NTL-GUI-ViewModels-WiredBoxViewModel-Protocols 'NTL.GUI.ViewModels.WiredBoxViewModel.Protocols')
  - [CanExecuteOpenPort(parameter)](#M-NTL-GUI-ViewModels-WiredBoxViewModel-CanExecuteOpenPort-System-Object- 'NTL.GUI.ViewModels.WiredBoxViewModel.CanExecuteOpenPort(System.Object)')
  - [ExecuteOpenPort(parameter)](#M-NTL-GUI-ViewModels-WiredBoxViewModel-ExecuteOpenPort-System-Object- 'NTL.GUI.ViewModels.WiredBoxViewModel.ExecuteOpenPort(System.Object)')

<a name='T-NTL-Examples-App'></a>
## App `type`

##### Namespace

NTL.Examples

##### Summary

Interaction logic for App.xaml

<a name='M-NTL-Examples-App-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='M-NTL-Examples-App-Main'></a>
### Main() `method`

##### Summary

Application Entry Point.

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-Converters-ArrayToStringConverter'></a>
## ArrayToStringConverter `type`

##### Namespace

NTL.GUI.Converters

<a name='M-NTL-GUI-Converters-ArrayToStringConverter-Convert-System-Object,System-Type,System-Object,System-Globalization-CultureInfo-'></a>
### Convert(value,targetType,parameter,culture) `method`

##### Summary

Converts a value.

##### Returns

A converted value. If the method returns null, the valid null value is used.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| value | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The value produced by the binding source. |
| targetType | [System.Type](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Type 'System.Type') | The type of the binding target property. |
| parameter | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The converter parameter to use. |
| culture | [System.Globalization.CultureInfo](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Globalization.CultureInfo 'System.Globalization.CultureInfo') | The culture to use in the converter. |

<a name='M-NTL-GUI-Converters-ArrayToStringConverter-ConvertBack-System-Object,System-Type,System-Object,System-Globalization-CultureInfo-'></a>
### ConvertBack(value,targetType,parameter,culture) `method`

##### Summary

Converts a value.

##### Returns

A converted value. If the method returns null, the valid null value is used.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| value | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The value that is produced by the binding target. |
| targetType | [System.Type](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Type 'System.Type') | The type to convert to. |
| parameter | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The converter parameter to use. |
| culture | [System.Globalization.CultureInfo](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Globalization.CultureInfo 'System.Globalization.CultureInfo') | The culture to use in the converter. |

<a name='T-NTL-GUI-ViewModels-BaseTestViewModel'></a>
## BaseTestViewModel `type`

##### Namespace

NTL.GUI.ViewModels

<a name='F-NTL-GUI-ViewModels-BaseTestViewModel-canRunTest'></a>
### canRunTest `constants`

##### Summary

The can run test

<a name='F-NTL-GUI-ViewModels-BaseTestViewModel-name'></a>
### name `constants`

##### Summary

The name

<a name='F-NTL-GUI-ViewModels-BaseTestViewModel-target'></a>
### target `constants`

##### Summary

The target

<a name='P-NTL-GUI-ViewModels-BaseTestViewModel-CanRunTest'></a>
### CanRunTest `property`

##### Summary

Gets or sets a value indicating whether this instance can run test.

<a name='P-NTL-GUI-ViewModels-BaseTestViewModel-IsTestRunning'></a>
### IsTestRunning `property`

##### Summary

Gets or sets a value indicating whether this instance is test running.

<a name='P-NTL-GUI-ViewModels-BaseTestViewModel-LocalHandler'></a>
### LocalHandler `property`

##### Summary

Gets or sets the local handler.

<a name='P-NTL-GUI-ViewModels-BaseTestViewModel-Name'></a>
### Name `property`

##### Summary

Gets or sets the name.

<a name='P-NTL-GUI-ViewModels-BaseTestViewModel-RunTest'></a>
### RunTest `property`

##### Summary

Gets the run test.

<a name='P-NTL-GUI-ViewModels-BaseTestViewModel-Target'></a>
### Target `property`

##### Summary

Gets or sets the target.

<a name='M-NTL-GUI-ViewModels-BaseTestViewModel-CanExecute-System-Object-'></a>
### CanExecute(parameters) `method`

##### Summary

Determines whether this instance can execute the specified parameters.

##### Returns

`true` if this instance can execute the specified parameters; otherwise, `false`.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| parameters | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The parameters. |

<a name='M-NTL-GUI-ViewModels-BaseTestViewModel-Execute-System-Object-'></a>
### Execute(parameters) `method`

##### Summary

Executes the specified parameters.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| parameters | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The parameters. |

<a name='T-NTL-GUI-ViewModels-BaseViewModel'></a>
## BaseViewModel `type`

##### Namespace

NTL.GUI.ViewModels

<a name='M-NTL-GUI-ViewModels-BaseViewModel-OnPropertyChanged-System-String-'></a>
### OnPropertyChanged(propertyName) `method`

##### Summary

Called when [property changed].

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| propertyName | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | Name of the property. |

<a name='T-NTL-GUI-CycleDesigner'></a>
## CycleDesigner `type`

##### Namespace

NTL.GUI

##### Summary

Interaction logic for CycleDesigner.xaml

<a name='M-NTL-GUI-CycleDesigner-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-CycleSelectionView'></a>
## CycleSelectionView `type`

##### Namespace

NTL.GUI

##### Summary

Interaction logic for CycleSelectionView.xaml

<a name='M-NTL-GUI-CycleSelectionView-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-ViewModels-EnumBaseViewModel'></a>
## EnumBaseViewModel `type`

##### Namespace

NTL.GUI.ViewModels

<a name='F-NTL-GUI-ViewModels-EnumBaseViewModel-itemsSource'></a>
### itemsSource `constants`

##### Summary

The items source

<a name='P-NTL-GUI-ViewModels-EnumBaseViewModel-ItemsSource'></a>
### ItemsSource `property`

##### Summary

Gets or sets the items source.

<a name='T-NTL-GUI-GenerateHeartBeatView'></a>
## GenerateHeartBeatView `type`

##### Namespace

NTL.GUI

##### Summary

Interaction logic for GenerateHeartbeatView.xaml

<a name='M-NTL-GUI-GenerateHeartBeatView-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-ViewModels-GenerateHeartBeatViewModel'></a>
## GenerateHeartBeatViewModel `type`

##### Namespace

NTL.GUI.ViewModels

<a name='P-NTL-GUI-ViewModels-GenerateHeartBeatViewModel-ActionLabel'></a>
### ActionLabel `property`

##### Summary

Gets or sets the action label.

<a name='P-NTL-GUI-ViewModels-GenerateHeartBeatViewModel-Period'></a>
### Period `property`

##### Summary

Gets or sets the period.

<a name='M-NTL-GUI-ViewModels-GenerateHeartBeatViewModel-Execute-System-Object-'></a>
### Execute(parameters) `method`

##### Summary

Executes the specified parameters.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| parameters | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The parameters. |

<a name='T-NTL-GUI-ViewModels-GenericBaseViewModel'></a>
## GenericBaseViewModel `type`

##### Namespace

NTL.GUI.ViewModels

##### Summary



##### See Also

- [NTL.GUI.BaseTestViewModel](#!-NTL-GUI-BaseTestViewModel 'NTL.GUI.BaseTestViewModel')

<a name='F-NTL-GUI-ViewModels-GenericBaseViewModel-inputs'></a>
### inputs `constants`

##### Summary

The inputs

<a name='F-NTL-GUI-ViewModels-GenericBaseViewModel-outputs'></a>
### outputs `constants`

##### Summary

The outputs

<a name='P-NTL-GUI-ViewModels-GenericBaseViewModel-Inputs'></a>
### Inputs `property`

##### Summary

Gets or sets the inputs.

<a name='P-NTL-GUI-ViewModels-GenericBaseViewModel-Outputs'></a>
### Outputs `property`

##### Summary

Gets or sets the outputs.

<a name='M-NTL-GUI-ViewModels-GenericBaseViewModel-Execute-System-Object-'></a>
### Execute(parameters) `method`

##### Summary

Executes the specified parameters.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| parameters | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The parameters. |

<a name='T-NTL-GUI-ViewModels-GetLoadDataResultViewModel'></a>
## GetLoadDataResultViewModel `type`

##### Namespace

NTL.GUI.ViewModels

<a name='P-NTL-GUI-ViewModels-GetLoadDataResultViewModel-Data'></a>
### Data `property`

##### Summary

Gets or sets the code.

<a name='P-NTL-GUI-ViewModels-GetLoadDataResultViewModel-DataSize'></a>
### DataSize `property`

##### Summary

Gets or sets the code.

<a name='P-NTL-GUI-ViewModels-GetLoadDataResultViewModel-RequestResult'></a>
### RequestResult `property`

##### Summary

Gets or sets the requestresult.

<a name='T-NTL-GUI-GetMCIErrorResultView'></a>
## GetMCIErrorResultView `type`

##### Namespace

NTL.GUI

##### Summary

Interaction logic for GetMCIErrorResultView.xaml

<a name='M-NTL-GUI-GetMCIErrorResultView-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel'></a>
## GetMCIErrorResultsViewModel `type`

##### Namespace

NTL.GUI.ViewModels

<a name='F-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-motorIndex'></a>
### motorIndex `constants`

##### Summary

The motor index

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-ClassBForcedToStop'></a>
### ClassBForcedToStop `property`

##### Summary

Gets or sets a value indicating whether [class b forced to stop].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-CurrentSensorField'></a>
### CurrentSensorField `property`

##### Summary

Gets or sets a value indicating whether [current sensor field].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-DCBusOutOfRange'></a>
### DCBusOutOfRange `property`

##### Summary

Gets or sets a value indicating whether [dc bus out of range].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-DCBusOverVoltage'></a>
### DCBusOverVoltage `property`

##### Summary

Gets or sets a value indicating whether [dc bus over voltage].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-DCBusUnderVoltage'></a>
### DCBusUnderVoltage `property`

##### Summary

Gets or sets a value indicating whether [dc bus under voltage].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-HWOverCurrent'></a>
### HWOverCurrent `property`

##### Summary

Gets or sets a value indicating whether [hw over current].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-InitializationFailed'></a>
### InitializationFailed `property`

##### Summary

Gets or sets a value indicating whether [initialization failed].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-InputCapturePlausibilityMaxFailed'></a>
### InputCapturePlausibilityMaxFailed `property`

##### Summary

Gets or sets a value indicating whether [input capture plausibility maximum failed].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-InputCapturePlausibilityMinFailed'></a>
### InputCapturePlausibilityMinFailed `property`

##### Summary

Gets or sets a value indicating whether [input capture plausibility minimum failed].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-InterruptDisabled'></a>
### InterruptDisabled `property`

##### Summary

Gets or sets a value indicating whether [interrupt disabled].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-InverterOverTemp'></a>
### InverterOverTemp `property`

##### Summary

Gets or sets a value indicating whether [inverter over temporary].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-LockedRotorAtStartup'></a>
### LockedRotorAtStartup `property`

##### Summary

Gets or sets a value indicating whether [locked rotor at startup].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-LockedRotorInRunning'></a>
### LockedRotorInRunning `property`

##### Summary

Gets or sets a value indicating whether [locked rotor in running].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-MCIErrorFound'></a>
### MCIErrorFound `property`

##### Summary

Gets or sets a value indicating whether [mci error found].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-MotorIndexInput'></a>
### MotorIndexInput `property`

##### Summary

Gets or sets the motor index input.

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-MotorOverheating'></a>
### MotorOverheating `property`

##### Summary

Gets or sets a value indicating whether [motor over heating].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-ObserverFailure'></a>
### ObserverFailure `property`

##### Summary

Gets or sets a value indicating whether [observer failure].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-PhaseLost'></a>
### PhaseLost `property`

##### Summary

Gets or sets a value indicating whether [phase lost].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-RequestResult'></a>
### RequestResult `property`

##### Summary

Gets or sets the requestresult.

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-SWOverCurrent'></a>
### SWOverCurrent `property`

##### Summary

Gets or sets a value indicating whether [sw over current].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-ShutdownHardwareFailed'></a>
### ShutdownHardwareFailed `property`

##### Summary

Gets or sets a value indicating whether [shutdown hardware failed].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-SpeedCheckFailed'></a>
### SpeedCheckFailed `property`

##### Summary

Gets or sets a value indicating whether [speed check failed].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-StratorOverTemp'></a>
### StratorOverTemp `property`

##### Summary

Gets or sets a value indicating whether [strator over temporary].

<a name='P-NTL-GUI-ViewModels-GetMCIErrorResultsViewModel-VoltageSensorField'></a>
### VoltageSensorField `property`

##### Summary

Gets or sets a value indicating whether [voltage sensor field].

<a name='T-NTL-GUI-GetMaxPackageSizeResultView'></a>
## GetMaxPackageSizeResultView `type`

##### Namespace

NTL.GUI

##### Summary

Interaction logic for GetMaxPackageSizeResultView.xaml

<a name='M-NTL-GUI-GetMaxPackageSizeResultView-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-ViewModels-GetMaxPackageSizeResultViewModel'></a>
## GetMaxPackageSizeResultViewModel `type`

##### Namespace

NTL.GUI.ViewModels

<a name='P-NTL-GUI-ViewModels-GetMaxPackageSizeResultViewModel-ReceiveMaxPackageSize'></a>
### ReceiveMaxPackageSize `property`

##### Summary

Gets or sets the code.

<a name='P-NTL-GUI-ViewModels-GetMaxPackageSizeResultViewModel-RequestResult'></a>
### RequestResult `property`

##### Summary

Gets or sets the requestresult.

<a name='P-NTL-GUI-ViewModels-GetMaxPackageSizeResultViewModel-SendMaxPackageSize'></a>
### SendMaxPackageSize `property`

##### Summary

Gets or sets the code.

<a name='T-NTL-GUI-GetMotorFVTResultView'></a>
## GetMotorFVTResultView `type`

##### Namespace

NTL.GUI

##### Summary

Interaction logic for GetMotorFVTResultView.xaml

<a name='M-NTL-GUI-GetMotorFVTResultView-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-ViewModels-GetMotorFVTResultViewModel'></a>
## GetMotorFVTResultViewModel `type`

##### Namespace

NTL.GUI.ViewModels

<a name='P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-CircuitOC'></a>
### CircuitOC `property`

##### Summary

Gets or sets CircuitOC.

<a name='P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-DCBus'></a>
### DCBus `property`

##### Summary

Gets or sets DCBus.

<a name='P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-DCBusVoltageClosed'></a>
### DCBusVoltageClosed `property`

##### Summary

Gets or sets DCBusVoltageClosed.

<a name='P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-DCBusVoltageOpen'></a>
### DCBusVoltageOpen `property`

##### Summary

Gets or sets DCBusVoltageOpen.

<a name='P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-ExpiredData'></a>
### ExpiredData `property`

##### Summary

Gets or sets ExpiredData.

<a name='P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-InvalidDataRead'></a>
### InvalidDataRead `property`

##### Summary

Gets or sets InvalidDataRead.

<a name='P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-MotorIndex'></a>
### MotorIndex `property`

##### Summary

Gets or sets the index of the motor.

<a name='P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-OC'></a>
### OC `property`

##### Summary

Gets or sets OC happened.

<a name='P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-PhaseCurrentA'></a>
### PhaseCurrentA `property`

##### Summary

Gets or sets PhaseCurrentA.

<a name='P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-PhaseCurrentB'></a>
### PhaseCurrentB `property`

##### Summary

Gets or sets PhaseCurrentB.

<a name='P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-PhaseCurrentC'></a>
### PhaseCurrentC `property`

##### Summary

Gets or sets PhaseCurrentC.

<a name='P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-PhaseVoltageA'></a>
### PhaseVoltageA `property`

##### Summary

Gets or sets PhaseVoltageA.

<a name='P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-PhaseVoltageB'></a>
### PhaseVoltageB `property`

##### Summary

Gets or sets PhaseVoltageB.

<a name='P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-PhaseVoltageC'></a>
### PhaseVoltageC `property`

##### Summary

Gets or sets PhaseVoltageC.

<a name='P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-RequestResult'></a>
### RequestResult `property`

##### Summary

Gets or sets the requestresult.

<a name='P-NTL-GUI-ViewModels-GetMotorFVTResultViewModel-TimedOut'></a>
### TimedOut `property`

##### Summary

Gets or sets Timedout.

<a name='T-NTL-GUI-Views-InputBaseView'></a>
## InputBaseView `type`

##### Namespace

NTL.GUI.Views

##### Summary

Interaction logic for InputBaseView.xaml

<a name='M-NTL-GUI-Views-InputBaseView-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-ViewModels-InputBaseViewModel'></a>
## InputBaseViewModel `type`

##### Namespace

NTL.GUI.ViewModels

##### Summary



##### See Also

- [NTL.GUI.BaseViewModel](#!-NTL-GUI-BaseViewModel 'NTL.GUI.BaseViewModel')

<a name='F-NTL-GUI-ViewModels-InputBaseViewModel-name'></a>
### name `constants`

##### Summary

The name

<a name='F-NTL-GUI-ViewModels-InputBaseViewModel-value'></a>
### value `constants`

##### Summary

The value

<a name='P-NTL-GUI-ViewModels-InputBaseViewModel-Name'></a>
### Name `property`

##### Summary

Gets or sets the name.

<a name='P-NTL-GUI-ViewModels-InputBaseViewModel-Value'></a>
### Value `property`

##### Summary

Gets or sets the value.

<a name='T-NTL-GUI-MainWindow'></a>
## MainWindow `type`

##### Namespace

NTL.GUI

##### Summary

Interaction logic for MainWindow.xaml

<a name='M-NTL-GUI-MainWindow-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-NTLTestModel'></a>
## NTLTestModel `type`

##### Namespace

NTL.GUI

<a name='P-NTL-GUI-NTLTestModel-StartFVTVM'></a>
### StartFVTVM `property`

##### Summary

Gets or sets the start FVTVM.

<a name='T-NTL-GUI-ViewModels-NucleusHandlerViewModel'></a>
## NucleusHandlerViewModel `type`

##### Namespace

NTL.GUI.ViewModels

<a name='M-NTL-GUI-ViewModels-NucleusHandlerViewModel-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the [NucleusHandlerViewModel](#T-NTL-GUI-ViewModels-NucleusHandlerViewModel 'NTL.GUI.ViewModels.NucleusHandlerViewModel') class.

##### Parameters

This constructor has no parameters.

<a name='F-NTL-GUI-ViewModels-NucleusHandlerViewModel-ntlViewModels'></a>
### ntlViewModels `constants`

##### Summary

The NTL view models

<a name='F-NTL-GUI-ViewModels-NucleusHandlerViewModel-receivedMessaged'></a>
### receivedMessaged `constants`

##### Summary

The received messaged

<a name='P-NTL-GUI-ViewModels-NucleusHandlerViewModel-Add'></a>
### Add `property`

##### Summary

Gets the add.

<a name='P-NTL-GUI-ViewModels-NucleusHandlerViewModel-ClearMessages'></a>
### ClearMessages `property`

##### Summary

Gets the clear messages.

<a name='P-NTL-GUI-ViewModels-NucleusHandlerViewModel-MethodToAdd'></a>
### MethodToAdd `property`

##### Summary

Gets or sets the method to add.

<a name='P-NTL-GUI-ViewModels-NucleusHandlerViewModel-MethodToRemove'></a>
### MethodToRemove `property`

##### Summary

Gets or sets the method to add.

<a name='P-NTL-GUI-ViewModels-NucleusHandlerViewModel-NTLViewModels'></a>
### NTLViewModels `property`

##### Summary

Gets or sets the NTL view models.

<a name='P-NTL-GUI-ViewModels-NucleusHandlerViewModel-NucleusHandlerMethods'></a>
### NucleusHandlerMethods `property`

##### Summary

Gets or sets the nucleus handler methods.

<a name='P-NTL-GUI-ViewModels-NucleusHandlerViewModel-NucleusHandlerMethodsView'></a>
### NucleusHandlerMethodsView `property`

##### Summary

Gets the nucleus handler methods view.

<a name='P-NTL-GUI-ViewModels-NucleusHandlerViewModel-ReceivedMessages'></a>
### ReceivedMessages `property`

##### Summary

Gets or sets the received messages.

<a name='P-NTL-GUI-ViewModels-NucleusHandlerViewModel-Remove'></a>
### Remove `property`

##### Summary

Gets the remove.

<a name='P-NTL-GUI-ViewModels-NucleusHandlerViewModel-SearchFilter'></a>
### SearchFilter `property`

##### Summary

Gets or sets the search filter.

<a name='P-NTL-GUI-ViewModels-NucleusHandlerViewModel-WiredBoxVM'></a>
### WiredBoxVM `property`

##### Summary

Gets or sets the wired box vm.

<a name='M-NTL-GUI-ViewModels-NucleusHandlerViewModel-AddViewModel-NTL-GUI-ViewModels-BaseTestViewModel-'></a>
### AddViewModel(viewModel) `method`

##### Summary

Adds the view model.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| viewModel | [NTL.GUI.ViewModels.BaseTestViewModel](#T-NTL-GUI-ViewModels-BaseTestViewModel 'NTL.GUI.ViewModels.BaseTestViewModel') | The view model. |

<a name='M-NTL-GUI-ViewModels-NucleusHandlerViewModel-AddViewModel-System-String-'></a>
### AddViewModel(taskName) `method`

##### Summary

Adds the view model.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| taskName | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | Name of the task. |

<a name='M-NTL-GUI-ViewModels-NucleusHandlerViewModel-GetMatchViewModel-System-String-'></a>
### GetMatchViewModel(taskName) `method`

##### Summary

Gets the match view model.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| taskName | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | Name of the task. |

<a name='M-NTL-GUI-ViewModels-NucleusHandlerViewModel-GetTypesFromNamespace-System-Reflection-Assembly,System-String-'></a>
### GetTypesFromNamespace(assembly,desiredNamespace) `method`

##### Summary

Gets the types from namespace.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| assembly | [System.Reflection.Assembly](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Reflection.Assembly 'System.Reflection.Assembly') | The assembly. |
| desiredNamespace | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The desired namespace. |

<a name='M-NTL-GUI-ViewModels-NucleusHandlerViewModel-WiredBoxVM_OpenPortExecuted-System-Object,System-EventArgs-'></a>
### WiredBoxVM_OpenPortExecuted(sender,e) `method`

##### Summary

Handles the OpenPortExecuted event of the WiredBoxVM control.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| sender | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The source of the event. |
| e | [System.EventArgs](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.EventArgs 'System.EventArgs') | The [EventArgs](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.EventArgs 'System.EventArgs') instance containing the event data. |

<a name='T-NTL-GUI-Views-OutputBaseView'></a>
## OutputBaseView `type`

##### Namespace

NTL.GUI.Views

##### Summary

Interaction logic for OutputBaseView.xaml

<a name='M-NTL-GUI-Views-OutputBaseView-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-ViewModels-OutputBaseViewModel'></a>
## OutputBaseViewModel `type`

##### Namespace

NTL.GUI.ViewModels

##### Summary



##### See Also

- [NTL.GUI.BaseViewModel](#!-NTL-GUI-BaseViewModel 'NTL.GUI.BaseViewModel')

<a name='F-NTL-GUI-ViewModels-OutputBaseViewModel-name'></a>
### name `constants`

##### Summary

The name

<a name='F-NTL-GUI-ViewModels-OutputBaseViewModel-value'></a>
### value `constants`

##### Summary

The value

<a name='P-NTL-GUI-ViewModels-OutputBaseViewModel-Name'></a>
### Name `property`

##### Summary

Gets or sets the name.

<a name='P-NTL-GUI-ViewModels-OutputBaseViewModel-Value'></a>
### Value `property`

##### Summary

Gets or sets the value.

<a name='T-NTL-GUI-PCcontrolView'></a>
## PCcontrolView `type`

##### Namespace

NTL.GUI

##### Summary

Interaction logic for SetLoadView.xaml

<a name='M-NTL-GUI-PCcontrolView-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-ViewModels-PCcontrolViewModel'></a>
## PCcontrolViewModel `type`

##### Namespace

NTL.GUI.ViewModels

<a name='P-NTL-GUI-ViewModels-PCcontrolViewModel-RequestResult'></a>
### RequestResult `property`

##### Summary

Gets or sets the requestresult.

<a name='M-NTL-GUI-ViewModels-PCcontrolViewModel-Execute-System-Object-'></a>
### Execute(parameters) `method`

##### Summary

Executes the specified parameters.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| parameters | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The parameters. |

<a name='T-NTL-GUI-ParallelProgrammingExample'></a>
## ParallelProgrammingExample `type`

##### Namespace

NTL.GUI

##### Summary

Interaction logic for ParallelProgrammingExample.xaml

<a name='M-NTL-GUI-ParallelProgrammingExample-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-PublishRegulationsResultView'></a>
## PublishRegulationsResultView `type`

##### Namespace

NTL.GUI

##### Summary

Interaction logic for GetMaxPackageSizeResultView.xaml

<a name='M-NTL-GUI-PublishRegulationsResultView-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-ViewModels-PublishRegulationsViewModel'></a>
## PublishRegulationsViewModel `type`

##### Namespace

NTL.GUI.ViewModels

<a name='P-NTL-GUI-ViewModels-PublishRegulationsViewModel-RequestResult'></a>
### RequestResult `property`

##### Summary

Gets or sets the requestresult.

<a name='T-NTL-GUI-RegulationsView'></a>
## RegulationsView `type`

##### Namespace

NTL.GUI

##### Summary

Interaction logic for RegulationsView.xaml

<a name='M-NTL-GUI-RegulationsView-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-ViewModels-RegulationsViewModel'></a>
## RegulationsViewModel `type`

##### Namespace

NTL.GUI.ViewModels

<a name='F-NTL-GUI-ViewModels-RegulationsViewModel-regulations'></a>
### regulations `constants`

##### Summary

Gets the regulations.

<a name='T-NTL-GUI-RelayCommand'></a>
## RelayCommand `type`

##### Namespace

NTL.GUI

##### Summary



##### See Also

- [System.Windows.Input.ICommand](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Windows.Input.ICommand 'System.Windows.Input.ICommand')

<a name='M-NTL-GUI-RelayCommand-#ctor-System-Action{System-Object},System-Func{System-Object,System-Boolean}-'></a>
### #ctor(execute,canExecute) `constructor`

##### Summary

Initializes a new instance of the [RelayCommand](#T-NTL-GUI-RelayCommand 'NTL.GUI.RelayCommand') class.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| execute | [System.Action{System.Object}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Action 'System.Action{System.Object}') | The execute. |
| canExecute | [System.Func{System.Object,System.Boolean}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Func 'System.Func{System.Object,System.Boolean}') | The can execute. |

<a name='F-NTL-GUI-RelayCommand-canExecute'></a>
### canExecute `constants`

##### Summary

The can execute

<a name='F-NTL-GUI-RelayCommand-execute'></a>
### execute `constants`

##### Summary

The execute

<a name='M-NTL-GUI-RelayCommand-CanExecute-System-Object-'></a>
### CanExecute(parameter) `method`

##### Summary

Defines the method that determines whether the command can execute in its current state.

##### Returns

true if this command can be executed; otherwise, false.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| parameter | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | Data used by the command.  If the command does not require data to be passed, this object can be set to null. |

<a name='M-NTL-GUI-RelayCommand-Execute-System-Object-'></a>
### Execute(parameter) `method`

##### Summary

Defines the method to be called when the command is invoked.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| parameter | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | Data used by the command.  If the command does not require data to be passed, this object can be set to null. |

<a name='M-NTL-GUI-RelayCommand-OnCanExecuteChanged'></a>
### OnCanExecuteChanged() `method`

##### Summary

Called when [can execute changed].

##### Parameters

This method has no parameters.

<a name='T-NTL-Examples-Properties-Resources'></a>
## Resources `type`

##### Namespace

NTL.Examples.Properties

##### Summary

A strongly-typed resource class, for looking up localized strings, etc.

<a name='P-NTL-Examples-Properties-Resources-Culture'></a>
### Culture `property`

##### Summary

Overrides the current thread's CurrentUICulture property for all
  resource lookups using this strongly typed resource class.

<a name='P-NTL-Examples-Properties-Resources-ResourceManager'></a>
### ResourceManager `property`

##### Summary

Returns the cached ResourceManager instance used by this class.

<a name='T-NTL-GUI-RevealHandlerExample'></a>
## RevealHandlerExample `type`

##### Namespace

NTL.GUI

##### Summary

Interaction logic for RevealHandlerExample.xaml

<a name='M-NTL-GUI-RevealHandlerExample-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-SetLoadDataView'></a>
## SetLoadDataView `type`

##### Namespace

NTL.GUI

##### Summary

Interaction logic for SetLoadView.xaml

<a name='M-NTL-GUI-SetLoadDataView-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-ViewModels-SetLoadDataViewModel'></a>
## SetLoadDataViewModel `type`

##### Namespace

NTL.GUI.ViewModels

<a name='P-NTL-GUI-ViewModels-SetLoadDataViewModel-Data'></a>
### Data `property`

##### Summary

Gets or sets the code.

<a name='P-NTL-GUI-ViewModels-SetLoadDataViewModel-DataSize'></a>
### DataSize `property`

##### Summary

Gets or sets the size of the data.

<a name='P-NTL-GUI-ViewModels-SetLoadDataViewModel-DataSizeVisibility'></a>
### DataSizeVisibility `property`

##### Summary

Gets or sets the data size visibility.

<a name='P-NTL-GUI-ViewModels-SetLoadDataViewModel-DataVisibility'></a>
### DataVisibility `property`

##### Summary

Gets or sets the data visibility.

<a name='P-NTL-GUI-ViewModels-SetLoadDataViewModel-LoadIdVisibility'></a>
### LoadIdVisibility `property`

##### Summary

Gets or sets the load identifier visibility.

<a name='P-NTL-GUI-ViewModels-SetLoadDataViewModel-RequestResult'></a>
### RequestResult `property`

##### Summary

Gets or sets the requestresult.

<a name='M-NTL-GUI-ViewModels-SetLoadDataViewModel-Execute-System-Object-'></a>
### Execute(parameters) `method`

##### Summary

Executes the specified parameters.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| parameters | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The parameters. |

<a name='T-NTL-GUI-Views-SettingFileDownloadView'></a>
## SettingFileDownloadView `type`

##### Namespace

NTL.GUI.Views

##### Summary

Interaction logic for SettingFileDownloadView.xaml

<a name='M-NTL-GUI-Views-SettingFileDownloadView-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-ViewModels-SettingFileDownloadViewModel'></a>
## SettingFileDownloadViewModel `type`

##### Namespace

NTL.GUI.ViewModels

<a name='P-NTL-GUI-ViewModels-SettingFileDownloadViewModel-SettingFilePath'></a>
### SettingFilePath `property`

##### Summary

Gets or sets the setting file path.

<a name='T-GetLoadTest-SimpleTaskmanager'></a>
## SimpleTaskmanager `type`

##### Namespace

GetLoadTest

##### Summary

SimpleTaskmanager

<a name='M-GetLoadTest-SimpleTaskmanager-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-StartAndGetMotorFVTResultView'></a>
## StartAndGetMotorFVTResultView `type`

##### Namespace

NTL.GUI

##### Summary

Interaction logic for GetMotorFVTResultView.xaml

<a name='M-NTL-GUI-StartAndGetMotorFVTResultView-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel'></a>
## StartAndGetMotorFVTResultViewModel `type`

##### Namespace

NTL.GUI.ViewModels

<a name='P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-CircuitOC'></a>
### CircuitOC `property`

##### Summary

Gets or sets CircuitOC.

<a name='P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-DCBus'></a>
### DCBus `property`

##### Summary

Gets or sets DCBus.

<a name='P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-DCBusVoltageClosed'></a>
### DCBusVoltageClosed `property`

##### Summary

Gets or sets DCBusVoltageClosed.

<a name='P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-DCBusVoltageOpen'></a>
### DCBusVoltageOpen `property`

##### Summary

Gets or sets DCBusVoltageOpen.

<a name='P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-Error'></a>
### Error `property`

##### Summary

Gets or sets the error.

<a name='P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-ExpiredData'></a>
### ExpiredData `property`

##### Summary

Gets or sets ExpiredData.

<a name='P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-InvalidDataRead'></a>
### InvalidDataRead `property`

##### Summary

Gets or sets InvalidDataRead.

<a name='P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-MotorIndex'></a>
### MotorIndex `property`

##### Summary

Gets or sets the index of the motor.

<a name='P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-OC'></a>
### OC `property`

##### Summary

Gets or sets OC happened.

<a name='P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-PhaseCurrentA'></a>
### PhaseCurrentA `property`

##### Summary

Gets or sets PhaseCurrentA.

<a name='P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-PhaseCurrentB'></a>
### PhaseCurrentB `property`

##### Summary

Gets or sets PhaseCurrentB.

<a name='P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-PhaseCurrentC'></a>
### PhaseCurrentC `property`

##### Summary

Gets or sets PhaseCurrentC.

<a name='P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-PhaseVoltageA'></a>
### PhaseVoltageA `property`

##### Summary

Gets or sets PhaseVoltageA.

<a name='P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-PhaseVoltageB'></a>
### PhaseVoltageB `property`

##### Summary

Gets or sets PhaseVoltageB.

<a name='P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-PhaseVoltageC'></a>
### PhaseVoltageC `property`

##### Summary

Gets or sets PhaseVoltageC.

<a name='P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-RequestResult'></a>
### RequestResult `property`

##### Summary

Gets or sets the requestresult.

<a name='P-NTL-GUI-ViewModels-StartAndGetMotorFVTResultViewModel-TimedOut'></a>
### TimedOut `property`

##### Summary

Gets or sets Timedout.

<a name='T-GetLoadTest-StartMotorFVTResultView'></a>
## StartMotorFVTResultView `type`

##### Namespace

GetLoadTest

##### Summary

StartMotorFVTResultView

<a name='T-NTL-GUI-StartMotorFVTResultView'></a>
## StartMotorFVTResultView `type`

##### Namespace

NTL.GUI

##### Summary

Interaction logic for StartMotorFVTResultView.xaml

<a name='M-GetLoadTest-StartMotorFVTResultView-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='M-NTL-GUI-StartMotorFVTResultView-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-ViewModels-StartMotorFVTResultViewModel'></a>
## StartMotorFVTResultViewModel `type`

##### Namespace

NTL.GUI.ViewModels

<a name='P-NTL-GUI-ViewModels-StartMotorFVTResultViewModel-Error'></a>
### Error `property`

##### Summary

Gets or sets the error.

<a name='P-NTL-GUI-ViewModels-StartMotorFVTResultViewModel-MotorIndex'></a>
### MotorIndex `property`

##### Summary

Gets or sets the index of the motor.

<a name='T-NTL-GUI-StopMotorFVTResultView'></a>
## StopMotorFVTResultView `type`

##### Namespace

NTL.GUI

##### Summary

Interaction logic for StopMotorFVTResultView.xaml

<a name='M-NTL-GUI-StopMotorFVTResultView-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-ViewModels-StopMotorFVTResultViewModel'></a>
## StopMotorFVTResultViewModel `type`

##### Namespace

NTL.GUI.ViewModels

<a name='P-NTL-GUI-ViewModels-StopMotorFVTResultViewModel-Code'></a>
### Code `property`

##### Summary

Gets or sets the code.

<a name='P-NTL-GUI-ViewModels-StopMotorFVTResultViewModel-RequestResult'></a>
### RequestResult `property`

##### Summary

Gets or sets the requestresult.

<a name='T-NTL-Examples-JabilTest-Test'></a>
## Test `type`

##### Namespace

NTL.Examples.JabilTest

<a name='M-NTL-Examples-JabilTest-Test-#ctor-NTL-Examples-JabilTest-ScriptVariableSpace,System-Object-'></a>
### #ctor(varSapce,otherParameters) `constructor`

##### Summary

Initializes a new instance of the [Test](#T-NTL-Examples-JabilTest-Test 'NTL.Examples.JabilTest.Test') class.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| varSapce | [NTL.Examples.JabilTest.ScriptVariableSpace](#T-NTL-Examples-JabilTest-ScriptVariableSpace 'NTL.Examples.JabilTest.ScriptVariableSpace') | The variable sapce. |
| otherParameters | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The other parameters. |

<a name='P-NTL-Examples-JabilTest-Test-VariableSpace'></a>
### VariableSpace `property`

##### Summary

Gets or sets the variable space.

<a name='T-NTL-Examples-ScriptProvider-UsingScriptProvider'></a>
## UsingScriptProvider `type`

##### Namespace

NTL.Examples.ScriptProvider

<a name='M-NTL-Examples-ScriptProvider-UsingScriptProvider-RunNucleusMethod-System-String,System-String[]-'></a>
### RunNucleusMethod(methodName,paramValues) `method`

##### Summary

Runs the a nucleus method.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| methodName | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | Name of the method. |
| paramValues | [System.String[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String[] 'System.String[]') | The parameter values. |

<a name='M-NTL-Examples-ScriptProvider-UsingScriptProvider-StartDevice-System-String,System-Byte-'></a>
### StartDevice(comPort,nodeAddress) `method`

##### Summary

Starts the device.
Open the com port

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| comPort | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The COM port. |
| nodeAddress | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') | The node address. |

<a name='M-NTL-Examples-ScriptProvider-UsingScriptProvider-StopDevice'></a>
### StopDevice() `method`

##### Summary

Stops the device.

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-VariableStreamExample'></a>
## VariableStreamExample `type`

##### Namespace

NTL.GUI

##### Summary

Interaction logic for VariableStreamExample.xaml

<a name='M-NTL-GUI-VariableStreamExample-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-Window1'></a>
## Window1 `type`

##### Namespace

NTL.GUI

##### Summary

Interaction logic for Window1.xaml

<a name='M-NTL-GUI-Window1-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-GetLoadTest-Window2'></a>
## Window2 `type`

##### Namespace

GetLoadTest

##### Summary

Window2

<a name='T-NTL-GUI-Window2'></a>
## Window2 `type`

##### Namespace

NTL.GUI

##### Summary

Interaction logic for Window2.xaml

<a name='M-GetLoadTest-Window2-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='M-NTL-GUI-Window2-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-Views-WiredBoxView'></a>
## WiredBoxView `type`

##### Namespace

NTL.GUI.Views

##### Summary

Interaction logic for WiredBoxView.xaml

<a name='M-NTL-GUI-Views-WiredBoxView-InitializeComponent'></a>
### InitializeComponent() `method`

##### Summary

InitializeComponent

##### Parameters

This method has no parameters.

<a name='T-NTL-GUI-ViewModels-WiredBoxViewModel'></a>
## WiredBoxViewModel `type`

##### Namespace

NTL.GUI.ViewModels

<a name='F-NTL-GUI-ViewModels-WiredBoxViewModel-port'></a>
### port `constants`

##### Summary

The port

<a name='F-NTL-GUI-ViewModels-WiredBoxViewModel-ports'></a>
### ports `constants`

##### Summary

The ports

<a name='P-NTL-GUI-ViewModels-WiredBoxViewModel-Address'></a>
### Address `property`

##### Summary

Gets or sets the address.

<a name='P-NTL-GUI-ViewModels-WiredBoxViewModel-Error'></a>
### Error `property`

##### Summary

Gets or sets the error.

<a name='P-NTL-GUI-ViewModels-WiredBoxViewModel-LocalHandler'></a>
### LocalHandler `property`

##### Summary

Gets or sets the local handler.

<a name='P-NTL-GUI-ViewModels-WiredBoxViewModel-OpenPort'></a>
### OpenPort `property`

##### Summary

Gets the open port.

<a name='P-NTL-GUI-ViewModels-WiredBoxViewModel-Port'></a>
### Port `property`

##### Summary

Gets or sets the port.

<a name='P-NTL-GUI-ViewModels-WiredBoxViewModel-PortStatusAction'></a>
### PortStatusAction `property`

##### Summary

Gets or sets the port status action.

<a name='P-NTL-GUI-ViewModels-WiredBoxViewModel-Ports'></a>
### Ports `property`

##### Summary

Gets or sets the ports.

<a name='P-NTL-GUI-ViewModels-WiredBoxViewModel-Protocol'></a>
### Protocol `property`

##### Summary

Gets or sets the protocol.

<a name='P-NTL-GUI-ViewModels-WiredBoxViewModel-Protocols'></a>
### Protocols `property`

##### Summary

Gets the protocols.

<a name='M-NTL-GUI-ViewModels-WiredBoxViewModel-CanExecuteOpenPort-System-Object-'></a>
### CanExecuteOpenPort(parameter) `method`

##### Summary

Determines whether this instance [can execute open port] the specified parameter.

##### Returns

`true` if this instance [can execute open port] the specified parameter; otherwise, `false`.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| parameter | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The parameter. |

<a name='M-NTL-GUI-ViewModels-WiredBoxViewModel-ExecuteOpenPort-System-Object-'></a>
### ExecuteOpenPort(parameter) `method`

##### Summary

Executes the open port.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| parameter | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The parameter. |
