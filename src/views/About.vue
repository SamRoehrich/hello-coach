<template>
  <div class="roster bg-gray-50 h-screen">
    <div class="max-w-7xl mx-auto px-2 sm:px-6 lg:px-8 flex flex-col">
      <div class="quick-info flex items-center">
        <div class="grid grid-cols-3 gap-4 w-1/2">
          <div>
            <p>Name: Sam Roehrich</p>
          </div>
          <div>
            <p>Age: 24</p>
          </div>
          <div>
            <p>Team: Comp/Travel/Rec</p>
          </div>
          <div>
            <a>USAC Profile</a>
          </div>
          <div>
            <a>Email</a>
          </div>
          <div>
            <p>Phone: 520-289-9596</p>
          </div>
          <div>
            <p>Height: 6 feet 1 inch</p>
          </div>
          <div>
            <p>Weight: 180 lb</p>
          </div>
          <div>
            Injured: No
          </div>
          <div>
            <button>Record Assessment</button>
          </div>
          <div>
            <button>View Records</button>
          </div>
          <div>
            <button>Delete Athlete Profile</button>
          </div>
        </div>
        <div class="ml-32">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            width="200"
            height="200"
            viewBox="0 0 30 30"
          >
            <circle cx="15" cy="15" r="15" fill="#A7C47E" />
            <path
              d="M 15 15 l 0 -15 a 15 15 0 0 1 14.27 10.36 z"
              fill="#78A343"
              stroke-linejoin="round"
            />
          </svg>
        </div>
      </div>
      <div class="flex mt-10">
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
