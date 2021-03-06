# osem-stuff
osem-stuff

* Photodiode: Hamamatsu S1223-01 [specsheet](https://www.hamamatsu.com/resources/pdf/ssd/s1223_series_kpin1050e.pdf)
  * Photosensitivity: 0.58 A/W at 950 nm
  * Preliminary tests: with 200 ohm series resistor, voltage across resistor is ~130 mV when 5V forward biased when LED shining right at the PD at close proximity
 
* LED: Vishay TSTS7100 [specsheet](https://www.vishay.com/docs/81047/tsts7100.pdf)
  * Wavelength: 950 nm
  * Forward voltage: 1.3 V
  * Typical foward current: 100mA
  * Max forward current: 250mA (T_case <= 25C)
  * Resistor in series: 37 ohm (5V), 20 ohm (3.3V)

* Lens: Comar Optics  08 PQ 06 [specsheet](https://www.comaroptics.com/pdf/08%c2%a0PQ%c2%a006.pdf)
  * Focal length: 8 mm
  * Diameter: 6.3 mm
  * Thickness: 3 mm

# Calibration
* osem 1
  * Linear range: ~1.15mm
  * Slope: -2.803V/mm, R^2 =  0.99818848
  * Max V: 3.973V
  * gain: 28.7K ohm (transimpedance amp.)
  * dark noise: ~0.00087V
