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
        <td class="schedule-week-num" rowspan=5>Week 1</td> <!-- Week Number -->
        <th>Mon 6/23</th> <!-- Date -->
        <td>
            Lec 1: Logistics + Abstraction<br/>
            <a href="#">(Recording 1)</a><br/>
            <a href="#">(Slides 1)</a>
        </td>
        <td></td> <!-- Lab -->
        <td></td> <!-- Discussion -->
        <td>            <a href="https://forms.gle/C6uKxjXNwCrPj4Kp8">
                Presemester Survey Released
            </a><br/><b>Due (FRI 6/27)</b></td> <!-- Assignment / Exam -->
    </tr>
    <tr>
        <th>Tue 6/24</th> <!-- Date -->
        <td>
            Lec 2: Functions + Conditional Logic<br/>
            <a href="#">(Recording 2)</a><br/>
            <a href="#">(Slides 2)</a>
        </td>
        <td><a href="/su25/lab_directory">Lab 0: Welcome to Snap!</a></td> <!-- Lab -->
        <td><a href="/su25/discussion">Disc 1</a></td> <!-- Discussion -->
        <td>  <a href="#">
                Project 1: Wordle-lite Released
            </a><br/><b>Due (MON 6/30)</b></td>
        </td>
    </tr>
    <tr>
        <th>Wed 6/25</th> <!-- Date -->
        <td>
            Lec 3: Iteration + Scoping<br/>
            <a href="#">(Recording 3)</a><br/>
            <a href="#">(Slides 3)</a>
        </td>
        <td><a href="/su25/lab_directory">Lab 1: Build Your Own Blocks</a></td> <!-- Lab -->
        <td></td> <!-- Discussion -->
        <td></td>
    </tr>
    <tr>
        <th>Thu 6/26</th> <!-- Date -->
        <td>
            Lec 4: Lists + Loops<br/>
            <a href="#">(Recording 4)</a><br/>
            <a href="#">(Slides 4)</a>
        </td>
        <td><a href="/su25/lab_directory">Lab 2: Conditionals, Reporters, and Testing</a></td> <!-- Lab -->
        <td><a href="/su25/discussion">Disc 2</a></td> <!-- Discussion -->
        <td></td>
    </tr>
    <tr>
        <th>Fri 6/27</th> <!-- Date -->
        <td></td> <!-- Lecture -->
        <td></td> <!-- Lab -->
        <td></td> <!-- Discussion -->
        <td></td> <!-- Assignment / Exam -->
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
        <td class="schedule-week-num" rowspan=5>Week 2</td> <!-- Week Number -->
        <th>Mon 6/30</th> <!-- Date -->
        <td>
            Lec 5: HOFs + Mutability vs Immutability + List Scoping<br/>
            <a href="#">(Recording 5)</a><br/>
            <a href="#">(Slides 5)</a>
        </td>
        <td><a href="/su25/lab_directory">Lab 3: Lists and Loops (Iteration)</a></td> <!-- Lab -->
        <td></td> <!-- Discussion -->
        <td> <b>Project 1: Wordle-lite Due</b>
        </td>
    </tr>
    <tr>
        <th>Tue 7/1</th> <!-- Date -->
        <td>
            Lec 6: Functions as Data + Lambdas<br/>
            <a href="#">(Recording 6)</a><br/>
            <a href="#">(Slides 6)</a>
        </td>
        <td><a href="/su25/lab_directory">Lab 4: Lists + HOFs</a></td> <!-- Lab -->
        <td><a href="/su25/discussion">Disc 3</a></td> <!-- Discussion -->
        <td>
            <a href="#">Project 2: Spelling Bee Released</a><br/><b>Due (MON 7/7)</b>
        </td>
    </tr>
    <tr>
        <th>Wed 7/2</th> <!-- Date -->
        <td>
            Lec 7: Nested Lists + Number Representation<br/>
            <a href="#">(Recording 7)</a><br/>
            <a href="#">(Slides 7)</a>
        </td>
        <td><a href="/su25/lab_directory">Lab 5: HOFs and Functions as Data</a></td> <!-- Lab -->
        <td></td> <!-- Discussion -->
        <td></td>
    </tr>
    <tr>
        <th>Thu 7/3</th> <!-- Date -->
        <td>
            In Person: Quiz 1<br/>
        </td>
        <td>Quest Preview</td> <!-- Lab with no link -->
        <td><a href="/su25/discussion">Disc 4</a></td> <!-- Discussion -->
        <td>Quiz 1</td> <!-- Assignment / Exam -->
    </tr>
    <tr>
        <th>Fri 7/4</th> <!-- Date -->
        <td colspan="4">NO CLASS (Holiday)</td>
        <td></td>
    </tr>
  </tbody>
</table>
