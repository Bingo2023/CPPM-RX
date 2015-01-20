# CPPM-RX
Simple Arduino library for RC receivers that output CPPM 

This is curerently configured for the Orange RX R615X Receiver from HobbyKing

Usage:
 *		StartCPPM(int) -- Run once in setup.  Pass the Arduino interrupt number (not pin number)
 * 
 *		To Access pulse widths use the following:
 *			RC_THROT
 *			RC_AILER
 *			RC_ELEV
 *			RC_RUDD
 *			RC_MODE
 *			RC_AUX1
 *			RC_AUX2
 *			RC_AUX3
 *		(See CPPM-RX.h to adjust pulse number if your receiver is different)
 *		
 *		RX_Fail() -- this function will return TRUE if last pulse was seen more than 0.5s ago