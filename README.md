# Wiegand Number Generator

The jar file is capable for converting decimal number to wiegand number format for below supported formats:
1. 26 bit
2. 30 bit
3. 34 bt
4. 37 but
5. 38 bit
6. 40 bit
7. 42 bit
8. 128 bit

#Example

public class DecimalToWiegand {

	public static void main(String[] args) {
	
		//WiegandService.ConvertDemimalToWiegandNumber(decimalNumber, facilityCode, wiegandFormat)
		
		try {
		
			System.out.println(WiegandService.ConvertDemimalToWiegandNumber(123, 0, 26));
			
		} catch (Exception e) {
		
			e.printStackTrace();
			
		}
	}
}
