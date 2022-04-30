# Parallel Web Crawler by OpenMP

/***************************************************************************
 *  CSCI-GA.3033-034 Multicore Processors, Spring 2022
 *  Instructor:          Mohamed Zahran, mzahran@cs.nyu.edu
 *
 *  Group Project 13:	 Parallel Web Crawler
 *			 Siwei Liu (sl9386)
 *			 Shang-Chuan Liu (sl9413)
 *			 Che-Hsien Chiu (cc7293)
 *			 Po-Yuan Huang (ph2291)
 *
 *  00_seq : sequential version, single crawler.
 *
 *  01_sq  : parallel version, multi-crawlers shared a link queue and a visited set.
 *
 *  02_ds  : parallel version, multi-crawlers own its' link queue and visited set.
 *
 *  03_ps  : nested parallel version, multi-crawlers own its' link queue and visited set.
 *           Able to parallel parsing webpage contain inside each crawler.                       
 *
 ***************************************************************************/
