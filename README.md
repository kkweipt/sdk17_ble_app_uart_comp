# sdk17_ble_app_uart_comp
SW  
This demo code is base on SDK17.02 ble_app_uart demo.  
Add nrfx_comp lib in the project.  
Set the threshold down to 60,set the threshold up to 63.   
Upzip this files to SDK, and the project path is nRF5_SDK_17.0.2_d674dde\examples\ble_peripheral\ble_app_uart_comp.    
   
   
HW  
Please use your Nordic nRF52DK as TEST Hardware.   
  
Test
Use AIN1(p.03)as V+ input ,use interval Vref as reference.  
When the V+ input is bigger then threshold up , you will get NRF_COMP_EVENT_UP event.  
When the V+ input is bigger then threshold down ,you will get NRF_COMP_EVENT_DOWN event.  
When you press the BUTTON1 on nRF52DK,it will sample the result immediately and give a return value.  

#These files for study only , can not use in your product!   
#Copyright belongs to me.   

