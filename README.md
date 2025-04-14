# CBT332
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 332 Contains the source for a started task which          *   FILE 332
//*           provides for job submission and automatic commands    *   FILE 332
//*           in an MVS JES2 environment.  It will provide          *   FILE 332
//*           enhanced automatic command execution and job          *   FILE 332
//*           submission at a specifiable time-of-day or            *   FILE 332
//*           day-of-week or day-of-the-month.  The source          *   FILE 332
//*           program has imbedded documentation on the format of   *   FILE 332
//*           the 'commands' pds.  Also in the source is a table    *   FILE 332
//*           of 'JCL' datasets which the started task will         *   FILE 332
//*           allocate and use to submit specified members to the   *   FILE 332
//*           internal reader.  These datasets are allocated by     *   FILE 332
//*           dynamic allocation and are de-allocated when          *   FILE 332
//*           finished processing.                                  *   FILE 332
//*                                                                 *   FILE 332
//*           Dale Chaney wrote the original program, and after     *   FILE 332
//*           these 30-odd years, it seems appropriate to give      *   FILE 332
//*           Dale the proper credit for this nice work.            *   FILE 332
//*                                                                 *   FILE 332
//*           A modified version of this program, which is running  *   FILE 332
//*           in production, has also been included in this file.   *   FILE 332
//*                                                                 *   FILE 332
//*           Another modified version of this program, which       *   FILE 332
//*           has been running under z/OS as high as release 1.11,  *   FILE 332
//*           has been put into this file as member AUTO.  Its      *   FILE 332
//*           load module is in XMIT format as member AUTOLOAD.     *   FILE 332
//*           This version of AUTO has been sent in by Glenn        *   FILE 332
//*           Siegel.                                               *   FILE 332
//*                                                                 *   FILE 332
//*           The old version, which doesn't seem to work anymore   *   FILE 332
//*           on z/OS, has been renamed AUTOOLD and has been        *   FILE 332
//*           replaced by the version from Glenn Siegel, which      *   FILE 332
//*           seems to work fine on z/OS, together with its load    *   FILE 332
//*           module, which is included here.                       *   FILE 332
//*                                                                 *   FILE 332
```
