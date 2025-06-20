I'll help you create a GitHub issue for adding learning functionality to your blind cube repository. Let me create a comprehensive issue that outlines the learning features that could be added.

```bash
cd /Users/Tom/GithubPublic/blind-cube && gh issue create --title "Add learning functionality" --body "## 🎓 Learning Functionality Enhancement

### Overview
Add comprehensive learning features to help users practice and improve their blind solving skills.

### Proposed Features

#### 📚 **Setup Move Learning**
- **Interactive Tutorial**: Step-by-step guide through setup moves for each letter
- **Practice Mode**: Random letter generation with hints and feedback
- **Progress Tracking**: Track which setup moves have been mastered
- **Spaced Repetition**: Focus on setup moves that need more practice

#### 🎯 **Algorithm Practice**
- **T Perm Practice**: Dedicated practice for edge permutations
- **Y Perm Practice**: Dedicated practice for corner permutations  
- **Parity Practice**: Practice for full parity algorithms
- **Algorithm Recognition**: Test ability to identify which algorithm to use

#### 📊 **Performance Analytics**
- **Speed Tracking**: Measure setup move execution time
- **Accuracy Metrics**: Track success rate for each letter/algorithm
- **Progress Charts**: Visual representation of improvement over time
- **Personal Records**: Track best times and streaks

#### 🎮 **Gamification**
- **Achievement System**: Badges for mastering different aspects
- **Daily Challenges**: Random setup move sequences to practice
- **Leaderboards**: Compare progress with other users (optional)
- **Streak Counter**: Track consecutive days of practice

#### 🧠 **Memory Training**
- **Letter Sequence Practice**: Practice memorizing letter sequences
- **Buffer Piece Training**: Focus on buffer piece recognition
- **Visual Memory**: Practice recalling cube states from memory
- **Auditory Cues**: Optional sound feedback for moves

#### 📱 **User Experience**
- **Customizable Interface**: Adjustable difficulty levels
- **Practice Sessions**: Timed practice sessions with goals
- **Review Mode**: Replay previous practice sessions
- **Export Data**: Save progress and statistics

### Technical Implementation

#### Frontend Features
- Add learning dashboard with progress overview
- Create practice mode interface
- Implement progress tracking system
- Add statistics and analytics display

#### Backend Requirements (if needed)
- User progress storage
- Statistics calculation
- Achievement system
- Data export functionality

#### Data Structure
```javascript
// Example progress tracking structure
{
  userId: string,
  setupMoves: {
    edge: { [letter]: { mastered: boolean, practiceCount: number, avgTime: number } },
    corner: { [letter]: { mastered: boolean, practiceCount: number, avgTime: number } }
  },
  algorithms: {
    tPerm: { mastered: boolean, practiceCount: number, avgTime: number },
    yPerm: { mastered: boolean, practiceCount: number, avgTime: number },
    parity: { mastered: boolean, practiceCount: number, avgTime: number }
  },
  statistics: {
    totalPracticeTime: number,
    sessionsCompleted: number,
    currentStreak: number,
    bestStreak: number
  }
}
```

### Priority Levels
1. **High Priority**: Setup move practice mode and progress tracking
2. **Medium Priority**: Algorithm practice and basic analytics
3. **Low Priority**: Gamification and advanced features

### Success Metrics
- User engagement with practice features
- Improvement in setup move recognition speed
- Increased practice session frequency
- User feedback on learning effectiveness

### Future Enhancements
- AI-powered difficulty adjustment
- Social features for learning groups
- Integration with competition preparation
- Mobile app version

---
*This issue is part of the blind solving learning enhancement initiative.*" --label "enhancement,learning,feature-request"
```
The command failed due to shell parsing issues with the complex body text. Let me create the issue with a simpler approach by creating a file first:

Now let me create the GitHub issue using the file:

```bash
gh issue create --title "Add learning functionality" --body-file issue_body.md --label "enhancement,learning,feature-request"
```
The issue was created but the 'learning' label doesn't exist. Let me create it with just the existing labels:

```bash
gh issue create --title "Add learning functionality" --body-file issue_body.md --label "enhancement,feature-request"
```
Let me check what labels are available and create the issue without labels first:

```bash
gh issue create --title "Add learning functionality" --body-file issue_body.md
```
Perfect! Now let me clean up the temporary file:

Ran tool
Excellent! I've successfully created a GitHub issue titled "Add learning functionality" in your blind-cube repository. 

## ✅ **Issue Created Successfully**

**Issue URL**: https://github.com/TumCucTom/blind-cube/issues/1

### 📋 **What the Issue Includes:**

#### **Comprehensive Learning Features**
- **Setup Move Learning**: Interactive tutorials, practice mode, progress tracking
- **Algorithm Practice**: Dedicated practice for T perm, Y perm, and parity
- **Performance Analytics**: Speed tracking, accuracy metrics, progress charts
- **Gamification**: Achievement system, daily challenges, streak counter
- **Memory Training**: Letter sequences, buffer piece recognition, visual memory
- **User Experience**: Customizable interface, practice sessions, review mode

#### **Technical Implementation Plan**
- Frontend features for learning dashboard
- Progress tracking system
- Statistics and analytics display
- Backend requirements (if needed)

#### **Priority Levels**
- High Priority: Setup move practice and progress tracking
- Medium Priority: Algorithm practice and basic analytics  
- Low Priority: Gamification and advanced features

#### **Success Metrics**
- User engagement with practice features
- Improvement in setup move recognition speed
- Increased practice session frequency
- User feedback on learning effectiveness

The issue is now live on your GitHub repository and ready for discussion, planning, and implementation! You can view it at the provided URL and add any additional details or modify the requirements as needed.