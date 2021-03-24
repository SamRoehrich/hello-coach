<template>
  <div class="roster bg-gray-50 h-screen">
    <div class="max-w-7xl mx-auto px-2 sm:px-6 lg:px-8 flex flex-col">
      <div class="quick-info h-96">
        <div class="w-full flex flex-col">
          <div class="flex items-center">
            <div class="w-1/5">
              <p>Name: Sam Roehrich</p>
            </div>
            <div class="w-1/5">
              <p>Age: 24</p>
            </div>
            <div class="w-1/5">
              <p>Team: Comp/Travel/Rec</p>
            </div>
            <div class="ml-20 w-1/5 bg-red-200 h-40">PHOTO</div>
          </div>
          <div class="flex w-3/5">
            <div class="flex-1">
              <a>USAC Profile</a>
            </div>
            <div class="flex-1">
              <p>Email</p>
            </div>
            <div class="flex-1">
              <p class="text-md">Phone: 520-289-9596</p>
            </div>
          </div>
          <div class="mt-10 w-3/5 buttons space-x-12 flex">
            <button>Record Assessment</button>
            <button>View Previous Assessments</button>
            <button>Delete Profile</button>
          </div>
        </div>
      </div>
      <div class="flex">
        <div class="w-1/2">
          <div class="schedule">
            <table class="table-auto">
              <thead>
                <tr>
                  <th>Catagory</th>
                  |
                  <th>Workout</th>
                  |
                  <th>3/22-3/29</th>
                  |
                  <th>3/30-4/4</th>
                  |
                  <th>4/5-4/11</th>
                  |
                  <th>4/6-4/13</th>
                </tr>
              </thead>
            </table>
          </div>
        </div>
        <div class="w-1/2">
          <div class="workout-list">
            <table class="table-fixed w-full">
              <thead>
                <tr>
                  <th>Workout</th>
                  <th>Catagory</th>
                  <th>Workload</th>
                  <th>Included</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td>4x4</td>
                  <td>PE</td>
                  <td>High</td>
                  <td>Yes</td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
