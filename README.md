module TugasAplikasi2 {
	public class Celcius {
	    double toFahrenheit(){
	        //°F = °C × 1,8 + 32
	        return (KonversiSuhu.SuhuAwal*1.8+32);
	    }
	    double toReamur(){
	        //°Ré = °C × 0,8
	        return (KonversiSuhu.SuhuAwal*0.8);
	    }
	    double toKelvin(){
	        //K = °C + 273,15
	        return (KonversiSuhu.SuhuAwal+273.15);
	    }
	}

	3. Ini merupakan class Fahrenheit sebagai "kalkulator" suhu yang berasal dari fahrenheit
	DATA HOSTED WITH ♥ BY PASTEBIN.COM - DOWNLOAD RAW - SEE ORIGINAL
	/**
	 *
	 * @author Agus
	 */
	public class Fahrenheit {
	    double toReamur(){
	        //°Ré = (°F − 32) / 2,25
	        return ((KonversiSuhu.SuhuAwal-32)/2.25);
	    }
	    double toKelvin(){
	        //K = (°F + 459,67) / 1,8
	        return ((KonversiSuhu.SuhuAwal+459.67)/ 1.8);
	    }
	    double toCelcius(){
	        //°C = (°F − 32) / 1,8
	        return ((KonversiSuhu.SuhuAwal-32)/1.8);
	    }
	}
}
