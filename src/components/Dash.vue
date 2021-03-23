<template>
  <div class="dash">
    <main class="bg-gray-50">
      <div class="max-w-7xl mx-auto px-2 sm:px-6 lg:px-8 flex">
        <div
          class="relative flex flex-col items-center justify-items-start space-y-6 h-auto"
        >
          <div class="h-auto w-auto rounded-sm border-gray-100 mr-10">
            <p class="text-xl">Home</p>
          </div>
          <div class="h-auto w-auto rounded-sm border-gray-100 mr-10">
            <p class="text-xl">Roster</p>
          </div>
          <div class="h-auto w-auto rounded-sm border-gray-100 mr-10">
            <p class="text-xl">Workouts</p>
          </div>
          <div class="h-auto w-auto rounded-sm border-gray-100 mr-10">
            <p class="text-xl">Notifications</p>
          </div>
          <div class="h-auto w-auto rounded-sm border-gray-100 mr-10">
            <p class="text-xl">Settings</p>
          </div>
        </div>
        <div class="h-screen w-full">
          <div class="cards flex space-x-4">
            <div class="rounded-lg shadow-lg h-40 w-1/3 bg-gray-50">
              <p>Athletes: 120</p>
            </div>
            <div class="rounded-lg shadow-lg h-40 w-1/3 bg-gray-50">
              <p>Workouts: 240</p>
            </div>
            <div class="rounded-lg shadow-lg h-40 w-1/3 bg-gray-50">
              <p>Pending Changes: 20</p>
            </div>
          </div>
          <p>Recent Activity</p>
          <table class="table-fixed w-full">
            <thead>
              <tr>
                <th class="">Date</th>
                <th class="w-1/5">Name</th>
                <th class="w-1/2">Workout</th>
                <th class="">Completed</th>
                <th class="">Comment</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>3/22</td>
                <td>Sam Roehrich</td>
                <td>1 on 1 off</td>
                <td>Yes</td>
                <td>Skin hurts</td>
              </tr>
              <tr>
                <td>3/22</td>
                <td>Sam Roehrich</td>
                <td>1 on 1 off</td>
                <td>Yes</td>
                <td>Skin hurts</td>
              </tr>
              <tr>
                <td>3/22</td>
                <td>Sam Roehrich</td>
                <td>1 on 1 off</td>
                <td>Yes</td>
                <td>Skin hurts</td>
              </tr>
              <tr>
                <td>3/22</td>
                <td>Sam Roehrich</td>
                <td>1 on 1 off</td>
                <td>Yes</td>
                <td>Skin hurts</td>
              </tr>
              <tr>
                <td>3/22</td>
                <td>Sam Roehrich</td>
                <td>1 on 1 off</td>
                <td>Yes</td>
                <td>Skin hurts</td>
              </tr>
              <tr>
                <td>3/22</td>
                <td>Sam Roehrich</td>
                <td>1 on 1 off</td>
                <td>Yes</td>
                <td>Skin hurts</td>
              </tr>
            </tbody>
          </table>
          <div class="more-cards flex space-x-4 py-20">
            <div class="rounded-lg shadow-lg h- w-1/2">
              <p>Coaches Connect</p>
            </div>
            <div class="rounded-lg shadow-lg h-40 w-1/2">
              <p>Competitions</p>
            </div>
          </div>
        </div>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "Dash",
};

// add pie charts to the admin cards.
// workouts will be sorted by type
// athletes by sub team
// changes by ??
</script>
