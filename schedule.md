<!-- Add styles for alternating row colors and borders -->
<style>
    .schedule-table {
        border-collapse: collapse;
        width: 100%;
        text-align: center;
    }
    .schedule-table th, .schedule-table td {
        border: 1px solid #A9A9A9; /* Darker border for all rows and columns */
        padding: 8px;
    }
</style>

<!-- Add a jump-to button to navigate to the current week -->
<p>
    <a href="#week1">Jump to Current Week</a>
</p>

<!-- Week 1 Calendar -->
<table class="table table-bordered schedule-table" id="week1">
  <thead>
    <tr>
      <th class="center schedule-week-num">Week</th>
      <th>Date</th>
      <th>Lecture</th>
      <th>Lab</th>
      <th>Discussion</th>
      <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
      <td class="schedule-week-num" rowspan="5">Week 1</td>
      <td>Mon 6/23</td>
      <td>
        Lec 1: Logistics + Abstraction<br/>
        <a href="https://bcourses.berkeley.edu/courses/1545431/external_tools/90481">(Recording 1)</a><br/>
        <a href="https://drive.google.com/drive/u/1/folders/1jWA6b59w5eAE7YCVH9y5MSRRwzwfRTAu">(Slides 1)</a>
      </td>
      <td></td>
      <td></td>
      <td>
        <a href="https://forms.gle/C6uKxjXNwCrPj4Kp8">Presemester Survey Released</a><br/><b>Due (FRI 6/27)</b>
      </td>
    </tr>
    <tr>
      <td>Tue 6/24</td>
      <td>
        Lec 2: Functions + Conditional Logic<br/>
        <a href="https://bcourses.berkeley.edu/courses/1545431/external_tools/90481">(Recording 2)</a><br/>
        <a href="https://drive.google.com/drive/u/1/folders/1ODyYdQmhNwUmhiI3YWUf2coX1t-IoiDD">(Slides 2)</a>
      </td>
      <td><a href="/su25/lab_directory">Lab 0: Welcome to Snap!</a></td>
      <td><a href="/su25/discussion">Disc 1</a></td>
      <td>
        <a href="https://cs10.org/su25/projects/project1/">Project 1: Wordle-lite Released</a><br/><b>Due (MON 6/30)</b>
      </td>
    </tr>
    <tr>
      <td>Wed 6/25</td>
      <td>
        Lec 3: Abstraction II: Number Representation<br/>
        <a href="https://bcourses.berkeley.edu/courses/1545431/external_tools/90481">(Recording 3)</a><br/>
        <a href="https://drive.google.com/drive/u/1/folders/1iu0r2YwZZdnAaO3m9DaTB1VcGYntlblk">(Slides 3)</a>
      </td>
      <td><a href="/su25/lab_directory">Lab 1: Build Your Own Blocks</a></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Thu 6/26</td>
      <td>
        Lec 4: Boolean Expressions, Variables, Iteration<br/>
        <a href="https://bcourses.berkeley.edu/courses/1545431/external_tools/90481">(Recording 4)</a><br/>
        <a href="https://drive.google.com/drive/folders/1dOHkaTlg_Pz-caL25kZl4zXnhzSrob2-?usp=drive_link">(Slides 4)</a>
      </td>
      <td><a href="/su25/lab_directory">Lab 2: Conditionals, Reporters, and Testing</a></td>
      <td><a href="/su25/discussion">Disc 2</a></td>
      <td></td>
    </tr>
    <tr>
      <td>Fri 6/27</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

<!-- Week 2 Calendar -->
<table class="table table-bordered schedule-table" id="week2">
  <thead>
    <tr>
      <th class="center schedule-week-num">Week</th>
      <th>Date</th>
      <th>Lecture</th>
      <th>Lab</th>
      <th>Discussion</th>
      <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
      <td class="schedule-week-num" rowspan="5">Week 2</td>
      <td>Mon 6/30</td>
      <td>
        Lec 5: Iterations + Lists <br/>
        <a href="https://bcourses.berkeley.edu/courses/1545431/external_tools/90481">(Recording 5)</a><br/>
        <a href="https://docs.google.com/presentation/d/1iF_tfpHAL0-0M8LX2Y96WdbT98OQeYKB67ab4Y-9ahU/edit?usp=sharing">(Slides 5)</a>
      </td>
      <td><a href="/su25/lab_directory">Lab 3: Lists and Loops (Iteration)</a></td>
      <td></td>
      <td>Project 1: Wordle-lite Due</td>
    </tr>
    <tr>
      <td>Tue 7/1</td>
      <td>
        Lec 6: Higher Order Functions (HoFs) <br/>
        <a href="https://bcourses.berkeley.edu/courses/1545431/external_tools/90481">(Recording 6)</a><br/>
        <a href="https://docs.google.com/presentation/d/1WbP9MukwZWUw7Ei7YFTrnh7iiI3kU29zjVXu4MhBU0I/edit?usp=sharing">(Slides 6)</a>
      </td>
      <td><a href="/su25/lab_directory">Lab 4: Lists + HOFs</a></td>
      <td><a href="/su25/discussion">Disc 3</a></td>
      <td>
        <a href="https://cs10.org/su25/projects/project2/">Project 2: Spelling Bee Released</a><br/><b>Due (WED 7/9)</b>
      </td>
    </tr>
    <tr>
      <td>Wed 7/2</td>
      <td>
        Lec 7: User Defined HOFs + Lambdas<br/>
        <a href="https://bcourses.berkeley.edu/courses/1545431/external_tools/90481">(Recording 7)</a><br/>
        <a href="https://docs.google.com/presentation/d/16q1dy-COACksDKM4TvuSrb1rA6jsAaX_VzBAXBCTFDw/edit?usp=sharing">(Slides 7)</a>
      </td>
      <td><a href="#">Quest Preview</a></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Thu 7/3</td>
      <td>In Person: Quiz 1</td>
      <td>No Lab</td>
      <td>No Discussion</td>
      <td>Quiz 1</td>
    </tr>
    <tr>
      <td>Fri 7/4</td>
      <td colspan="4">NO CLASS (Holiday)</td>
      <td></td>
    </tr>
  </tbody>
</table>
<!-- Week 3 Calendar -->
<table class="table table-bordered schedule-table" id="week3">
  <thead>
    <tr>
      <th class="center schedule-week-num">Week</th>
      <th>Date</th>
      <th>Lecture</th>
      <th>Lab</th>
      <th>Discussion</th>
      <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
      <td class="schedule-week-num" rowspan="5">Week 3</td>
      <td>Mon 7/7</td>
      <td>
        Lec 8: Nested Lists<br/>
        <a href="https://bcourses.berkeley.edu/courses/1545431/external_tools/90481">(Recording 8)</a><br/>
        <a href="https://docs.google.com/presentation/d/1rIJSkU8c0-LMEz5DhTRkA5fZcLrDRBCJmx1L4RpXjYE/edit?usp=sharing">(Slides 8)</a>
      </td>
      <td><a href="/su25/lab_directory">Lab 5: Boards</a></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Tue 7/8</td>
      <td>
        Lec 9: Recursion<br/>
        <a href="https://bcourses.berkeley.edu/courses/1545431/external_tools/90481">(Recording 9)</a><br/>
        <a href="https://docs.google.com/presentation/d/11QX5pbCe7GY-84yd4a29xo6CiHQPwMm32kYFM3RkMtc/edit?usp=sharing">(Slides 9)</a>
      </td>
      <td><a href="/su25/lab_directory">Lab 6: Recursive Reporters</a></td>
      <td><a href="/su25/discussion">Disc 5</a></td>
      <td></td>
    </tr>
    <tr>
      <td>Wed 7/9</td>
      <td>Lec 10: Fractal / Tree Recursion<br/>
        <a href="https://bcourses.berkeley.edu/courses/1545431/external_tools/90481">(Recording 10)</a><br/>
        <a href="https://drive.google.com/drive/folders/1DcsxgHwqei1fVFBLiL_--yPaCxLAMxmp?usp=sharing">(Slides 10)</a>
      </td>
      <td><a href="/su25/lab_directory">Lab 7: Fractals</a></td>
      <td></td>
      <td><b>Project 2: Spelling Bee Due</b></td>
    </tr>
    <tr>
      <td>Thu 7/10</td>
      <td>Lec 11: Algorithms & Algorithmic Complexity<br/>
        <a href="https://bcourses.berkeley.edu/courses/1545431/external_tools/90481">(Recording 11)</a><br/>
        <a href="https://docs.google.com/presentation/d/1DLXsHSI22eZgMaNzVFN8tcKclH0RFaSjsoHjWqSuOrU/edit?usp=sharing">(Slides 11)</a>
      </td>
      <td><a href="/su25/lab_directory">Lab 8: Algorithms</a></td>
      <td><a href="/su25/discussion">Disc 6</a></td>
      <td>
        <a href="#">Project 3: 2048 Released</a><br/>
        <b>Due (Mon 7/21)</b>
      </td>
    </tr>
    <tr>
      <td>Fri 7/11</td>
      <td></td>
      <td></td>
      <td></td>
      <td>
        <b>Quiz 1 Retake</b><br/>
        Location: GPBB 100<br/>
        Time: 4–5 PM
      </td>
    </tr>
  </tbody>
</table>

<!-- Week 4 Calendar -->
<table class="table table-bordered schedule-table" id="week4">
  <thead>
    <tr>
      <th class="center schedule-week-num">Week</th>
      <th>Date</th>
      <th>Lecture</th>
      <th>Lab</th>
      <th>Discussion</th>
      <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
      <td class="schedule-week-num" rowspan="5">Week 4</td>
      <td>Mon 7/14</td>
      <td>
        Lec 12: Data Science<br/>
        <a href="https://bcourses.berkeley.edu/courses/1545431/external_tools/90481">(Recording 12)</a><br/>
        <a href="https://docs.google.com/presentation/d/1vlj7ANkN0IwmbOw7TgqIOXwLqXiDTTFHa53N7ox_1Tw/edit?usp=sharing">(Slides 12)</a>
      </td>
      <td><a href="/su25/lab_directory">Lab 9: Algorithmic Complexity</a></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Tue 7/15</td>
      <td>
        Lec 13: AI, ML, and LLMs<br/>
        <a href="https://bcourses.berkeley.edu/courses/1545431/external_tools/90481">(Recording 13)</a><br/>
        <a href="https://docs.google.com/presentation/d/1_0NKs34BS_qiVZn9iCmbvu5EM6zrfyU00y-U3a1IkF0/edit?usp=sharing">(Slides 13)</a>
      </td>
      <td><a href="/su25/lab_directory">Lab 10: Data Science</a></td>
      <td><a href="/su25/discussion">Disc 7</a></td>
      <td></td>
    </tr>
    <tr>
      <td>Wed 7/16</td>
      <td>
        Lec 14: Social Implications - AI Usage in the Classroom (Guest Stacey Yoo)<br/>
        <a href="https://bcourses.berkeley.edu/courses/1545431/external_tools/90481">(Recording 14)</a><br/>
          <a href="https://drive.google.com/drive/folders/1j-RPg9lxUO9tafqmU0iYkCv2VA6uVpjr?usp=sharing">(Slides 14)</a>
      </td>
      <td><a href="/su25/lab_directory">Lab: Quiz 2 Preview</a></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Thu 7/17</td>
      <td>
        Quiz 2 Review<br/>
        <a href="https://bcourses.berkeley.edu/courses/1545431/external_tools/90481">(Recording 15)</a>
      </td>
      <td><a href="/su25/lab_directory">Lab: Quiz 2 Practice</a></td>
      <td><a href="/su25/discussion">Disc 8</a></td>
      <td></td>
    </tr>
    <tr>
      <td>Fri 7/18</td>
      <td></td>
      <td></td>
      <td></td>
      <td>
        <b>Quiz 2</b><br/>
        Location: GPBB 100<br/>
        Time: 4–5 PM
      </td>
    </tr>
  </tbody>
</table>
