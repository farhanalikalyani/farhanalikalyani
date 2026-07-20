<div align="center">

```
╔═══════════════════════════════════════════════════════════════════╗
║                                                                     ║
║   $ whoami                                                         ║
║   farhan_ali                                                       ║
║                                                                     ║
║   $ cat /etc/motto                                                 ║
║   "Access shouldn't depend on where you were born."                ║
║                                                                     ║
║   $ status                                                         ║
║   [ONLINE] Lahore, Pakistan  |  Building in public  |  Terminal open║
║                                                                     ║
╚═══════════════════════════════════════════════════════════════════╝
```

</div>

<br/>

## `class FarhanAli extends Human`

```javascript
class FarhanAli extends Human {
  constructor() {
    super();
    this.based_in    = "Lahore, Pakistan";
    this.studying    = "Computer Science";
    this.building    = "Future With Farhan — EdTech for students who got told 'no' too many times";
    this.languages   = ["C++", "Java", "JavaScript", "Python"];
    this.stack       = ["React Native", "Expo", "Firebase", "Qt", "Node.js"];
    this.mode        = "shipping > theorizing";
  }

  why() {
    // I grew up watching sharper people than me lose
    // not because they lacked ability, but because they
    // lacked a single person telling them what to do next.
    // That's not a talent gap. That's a distribution problem.
    // I build software to fix distribution problems.
    return this.building;
  }
}
```

<br/>

## `$ git log --oneline --graph --author="Farhan Ali"`

```
* 7a3f9c1  (HEAD -> main) refactor(fwf): dark navy theme + expandable detail cards
* 2b8e4d0  feat(fwf): converted business proposal to PDF for PMYBALS loan application
* 91c7a22  feat(ai-study-buddy): AI-generated flashcards + MCQ quizzes from raw notes
* f04d813  fix(ai-study-buddy): resolved CORS silent-fail on web, moved testing to Expo Go
* 5e1a9b7  build(ansarul-khair): shipped working APK, avoided nav-lib crash conflicts
* c390fe2  feat(hms-nexus-pro): added Qt Charts, CSV export, backup/restore
* 8817bcd  fix(univault): resolved file I/O name-parsing bug corrupting saved data
* 1d0f662  init: started writing code because reading about it stopped being enough
```

<br/>

## `// stack_trace.log` — things that broke, and what they taught me

```
Traceback (most recent call last):
  File "hms_nexus_pro.cpp", line 214, in <buildChart>
QBarCategoryAxis::append — ambiguous overload
  → Lesson: compilers don't care how confident you are. Read the signature twice.

Traceback (most recent call last):
  File "univault.cpp", line 88, in <loadRecord>
DataCorruptionError: file I/O name parsing broke on reload
  → Lesson: the bug is rarely where you're staring. It's one function upstream.

Traceback (most recent call last):
  File "aiService.js", line 41, in <fetchSummary>
NetworkError: silent failure, no response
  → Lesson: "it doesn't work" is not a debugging step. Read the browser console,
    then test on the actual device it's meant to run on.

Exception handled. Process resumed. No exceptions were fatal — only unfinished.
```

<br/>

## `$ npm test` — running FarhanAli.values.test.js

```
 PASS  ./values.test.js

  Core Values
    ✓ ships working software over polished theory (4ms)
    ✓ reads the actual error before guessing (2ms)
    ✓ chooses boring/stable tech when real users depend on it (3ms)
    ✓ treats every small project as reps for the big one (1ms)
    ✓ believes education is infrastructure, not a luxury (0ms)

  Test Suites: 1 passed, 1 total
  Tests:       5 passed, 5 total
  Time:        ongoing, indefinitely
```

<br/>

## `README.md` — Future With Farhan `[in_progress]`

```yaml
project: Future With Farhan (FWF)
type: EdTech mobile application
stack: [Expo, React Native, Firebase]
for: Pakistani students navigating exams, scholarships, universities, careers
status: mid-rebuild — dark navy UI system, branded identity, smart search/filter,
        expandable detail cards, AI mentoring layer, mock test engine
funding: business proposal submitted under PMYBALS (Prime Minister's Youth
         Business & Agriculture Loan Scheme)
thesis: >
  A student's postal code should not decide whether they know a
  scholarship deadline exists. Software can fix that. So I'm fixing it.
```

<br/>

## Also in the repo history

```
📦 ai-study-buddy      → paste notes, get AI flashcards + quizzes (Claude API + Expo)
📦 ansarul-khair       → charity app for a Pakistani trust, stable APK, Firestore backend
📦 hms-nexus-pro       → commercial-grade hospital management system, C++/Qt
📦 univault            → campus management system, C++, custom 3D-array data layer
📦 library-mgmt-system → Java Swing, OOP demonstration: inheritance, I/O, exceptions
```

<br/>

## `$ man farhan`

```
NAME
       farhan — developer, student, occasional 2am debugger

SYNOPSIS
       farhan [--help-a-friend] [--ship-something] [--fix-a-bug-in-your-life]

DESCRIPTION
       Builds mobile and web software independently and for others.
       Currently rebuilding Future With Farhan into something that
       could genuinely change a student's semester.

       Does not do hype. Does do working code.

SEE ALSO
       github.com/relento_coder
```

<br/>

<div align="center">

```
$ echo "if you're building something that helps people, open an issue —
         I'll probably show up with opinions and a pull request."
```

**No badges. No widgets. Just the log of someone building something that matters.**

</div>
