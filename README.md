# Parallel Web Crawler by OpenMP

/***************************************************************************
 *  CSCI-GA.3033-034 Multicore Processors, Spring 2022
 *  Instructor: Mohamed Zahran
 *
 *  Group Project 13:	 Parallel Web Crawler by OpenMP
 *
 *  00_seq : sequential version, single crawler.
 *  01_sq  : multi-crawlers shared a link queue and a visited set.
 *  02_ds  : crawlers own its' link queue and visited set.
 *  03_ps  : nested parallel section multi-crawlers own its' link queue and visited set.
 *           able to parallel parsing webpage contain inside each crawler.  
 ***************************************************************************/
