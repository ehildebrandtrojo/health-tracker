<script>
    coords = {
        "LOS ROBLES HOSPITAL & MEDICAL CENTER - EAST CAMPUS" : [-13226507.2733,4049625.5534],
        "EAST LOS ANGELES DOCTORS HOSPITAL" :[-13156201.0459, 4031977.7232 ],
        "SOUTHERN CALIFORNIA HOSPITAL AT HOLLYWOOD" : [-13171904.8938, 4041752.3856 ],
        "KINDRED HOSPITAL BALDWIN PARK" : [-13132075.1047, 4037269.7587 ],
        "LAKEWOOD REGIONAL MEDICAL CENTER" : [-13152220.0561,4009979.5733 ],
        "MONROVIA MEMORIAL HOSPITAL" : [-13134883.6809, 4048794.2127],
        "MONTEREY PARK HOSPITAL" : [-13151091.1948, 4035446.0448],
        "STAR VIEW ADOLESCENT - P H F" : [-13175340.4444, 4005182.4762]
    }
</script>
<div class="mt-10 sm:mt-0">
    <div class="md:grid md:grid-cols-3 md:gap-6">
      <div class="md:col-span-1">
        <div class="px-4 sm:px-0">
          <h3 class="text-lg font-medium leading-6 text-gray-900">Personal Information</h3>
          <p class="mt-1 text-sm text-gray-600">Please fill out your contact information, the disease you may have contracted and the hospital you have stayed in.</p>
        </div>
      </div>

      <div class="mt-5 md:col-span-4 md:mt-0">
        <form action="#" method="POST">
          <div class="overflow-hidden shadow sm:rounded-md">
            <div class="bg-white px-4 py-5 sm:p-6">
              <div class="grid grid-cols-6 gap-6">
                <div class="col-span-6 sm:col-span-3">
                  <label for="first-name" class="block text-sm font-medium text-gray-700">First name</label>
                  <input type="text" name="first-name" id="first-name" autocomplete="given-name" class="h-10 mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm">
                </div>
  
                <div class="col-span-6 sm:col-span-3">
                  <label for="last-name" class="block text-sm font-medium text-gray-700">Last name</label>
                  <input type="text" name="last-name" id="last-name" autocomplete="family-name" class="h-10 mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm">
                </div>
  
                <div class="col-span-6 sm:col-span-4">
                  <label for="email-address" class="block text-sm font-medium text-gray-700">Email address</label>
                  <input type="text" name="email-address" id="email-address" autocomplete="email" class="h-10 mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm">
                </div>

                <div class="col-span-6 sm:col-span-3">
                    <label for="phone-number" class="block text-sm font-medium text-gray-700">Phone Number</label>
                    <input type="text" name="phone-number" id="phone-number" autocomplete="phone" class="h-10 mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm">
                  </div>    
  
                <div class="col-span-6 sm:col-span-3">
                  <label for="gender" class="block text-sm font-medium text-gray-700">Gender</label>
                  <select id="gender" name="gender" autocomplete="country-name" class="mt-1 block w-full rounded-md border border-gray-300 bg-white py-2 px-3 shadow-sm focus:border-indigo-500 focus:outline-none focus:ring-indigo-500 sm:text-sm">
                    <option>Male</option>
                    <option>Female</option>
                    <option>Other</option>
                    <option>Unknown</option>
                  </select>
                </div>

                <div class="col-span-6 sm:col-span-6 lg:col-span-2">
                    <label for="age" class="block text-sm font-medium text-gray-700">Age</label>
                    <input type="text" name="age" id="age" autocomplete="address-level2" class="h-10 mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm">
                  </div>
  
                <div class="col-span-6 sm:col-span-3 lg:col-span-2">
                  <label for="hospital-name" class="block text-sm font-medium text-gray-700">Hospital name</label>
                  <input type="text" name="hospital-name" id="hospital-name" autocomplete="hospital-name" class="h-10 mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm">
                  <select id="gender" name="gender" autocomplete="country-name" class="mt-1 block w-full rounded-md border border-gray-300 bg-white py-2 px-3 shadow-sm focus:border-indigo-500 focus:outline-none focus:ring-indigo-500 sm:text-sm">
                    <option>LOS ROBLES HOSPITAL & MEDICAL CENTER - EAST CAMPUS</option>
                    <option>EAST LOS ANGELES DOCTORS HOSPITAL</option>
                    <option>SOUTHERN CALIFORNIA HOSPITAL AT HOLLYWOOD</option>
                    <option>KINDRED HOSPITAL BALDWIN PARK</option>

                    <option>LAKEWOOD REGIONAL MEDICAL CENTER</option>
                    <option>MONROVIA MEMORIAL HOSPITAL</option>
                    <option>MONTEREY PARK HOSPITAL</option>
                    <option>STAR VIEW ADOLESCENT - P H F</option>
                   </select>                 
                </div>

                <div class="col-span-6 sm:col-span-3 lg:col-span-2">
                    <label for="state" class="block text-sm font-medium text-gray-700">State</label>
                    <input type="text" name="state" id="state" autocomplete="state" class="h-10 mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm">
                </div>
  
  
                <div class="col-span-6 sm:col-span-3 lg:col-span-2">
                  <label for="patient-id" class="block text-sm font-medium text-gray-700">Patient ID</label>
                  <input type="text" name="patient-id" id="patient-id" autocomplete="address-level1" class="h-10 mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm">
                </div>
  
                <div class="col-span-6 sm:col-span-3 lg:col-span-2">
                  <label for="disease" class="block text-sm font-medium text-gray-700">Disease</label>
                  <input type="text" name="disease" id="disease" autocomplete="postal-code" class="h-10 mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm">
                </div>

                <div class="col-span-6 sm:col-span-3 lg:col-span-2">
                    <label for="symptoms" class="block text-sm font-medium text-gray-700">Symptoms</label>
                    <input type="text" name="symptoms" id="symptoms" autocomplete="postal-code" class="h-10 mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm">
                </div>


                
            </div>


    
            <div class="mt-1 flex justify-center justify-items-stretch rounded-md border-2 border-dashed border-gray-300 px-6 pt-5 pb-6">
                <div class="space-y-1 text-center">
                  <svg class="mx-auto h-12 w-12 text-gray-400" stroke="currentColor" fill="none" viewBox="0 0 48 48" aria-hidden="true">
                    <path d="M28 8H12a4 4 0 00-4 4v20m32-12v8m0 0v8a4 4 0 01-4 4H12a4 4 0 01-4-4v-4m32-4l-3.172-3.172a4 4 0 00-5.656 0L28 28M8 32l9.172-9.172a4 4 0 015.656 0L28 28m0 0l4 4m4-24h8m-4-4v8m-12 4h.02" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
                  </svg>
                  <div class="flex text-sm text-gray-600">
                    <label for="file-upload" class="relative cursor-pointer rounded-md bg-white font-medium text-indigo-600 focus-within:outline-none focus-within:ring-2 focus-within:ring-indigo-500 focus-within:ring-offset-2 hover:text-indigo-500">
                      <span>Upload a file</span>
                      <input id="file-upload" name="file-upload" type="file" class="sr-only">
                    </label>
                    <p class="pl-1">or drag and drop</p>
                  </div>
                  <p class="text-xs text-gray-500">PNG, JPG, GIF up to 10MB</p>
                </div>
          </div>

            <div class="bg-gray-50 px-4 py-3 text-right sm:px-6">
              <button type="submit" class="inline-flex justify-center rounded-md border border-transparent bg-indigo-600 py-2 px-4 text-sm font-medium text-white shadow-sm hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:ring-offset-2">Submit</button>
            </div>
          </div>
        </form>
      </div>
    </div>
  </div>

