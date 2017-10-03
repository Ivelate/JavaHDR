Java HDR Image Writer / Reader

Usage:
-Reading: Invoke HDREncoder.readHDR(File f,boolean rgb) passing through the .hdr file to read. Results will be returned inside a HDRImage object which contains helper methods to get the value of each channel of each pixel. If <rgb> is set to false, only the red channel of the .hdr image will be read

-Writing: Invoke HDREncoder.writeHDR(HDRImage img,File file) passing through a HDRImage class already filled with the data you want. This class has helper methods to set each pixel to the value you desire

That's it! Easy!