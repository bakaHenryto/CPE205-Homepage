<template>
    <!-- Services section start -->
	<section id="services-section" class="px-12 lg:px-32 py-16 relative overflow-hidden">
        <!-- Text wrapper start -->
        <div class="flex gap-8 flex-col md:flex-row">
            <!-- Main text start -->
            <h1 class="uppercase text-5xl mb-4 font-semibold ">
                SERVICES
            </h1>
            <p class="capitalize xl:w-1/2 text-stone-500 mb-8">
                A social application designed for doctors, patients, and pharmacies can bring significant benefits to the healthcare industry. With this platform, doctors can connect with their patients in a more efficient and convenient way. Patients can book appointments with their preferred doctors, receive reminders for upcoming appointments, and even communicate with their physicians in case of emergencies. 
            </p>
            <!-- Main text end -->
        </div>
        <!-- Text wrapper end -->

        <!-- Services start -->
        <div class="flex flex-col md:flex-row md:gap-8">
            <!-- Wedding service start -->
            <div class="flex flex-row md:flex-col justify-between md:justify-start items-center md:items-start my-8 md:w-1/3">
                <img src="./DoctorLogo.png" height="90" width="90" alt="Wedding" class="-z-50 md:mb-4">
                <div class="w-2/3 text-right md:text-left md:w-full">
                    <h1 class="uppercase text-2xl font-semibold">
                        Doctors
                    </h1>
                    <p class="capitalize text-stone-500">
                        With the app, doctors can communicate more efficiently with their patients, saving time and resources.
                    </p>
                </div>
            </div>
            <!-- Wedding service end -->

            <!-- Wedding service start -->
            <div class="flex flex-row md:flex-col justify-between items-center md:items-start my-8 md:w-1/3">
                <div class="w-2/3 text-left md:w-full md:order-2">
                    <h1 class="uppercase text-2xl font-semibold">
                        Patients
                    </h1>
                    <p class="capitalize text-stone-500">
                        Patients can use the app to book appointments with their doctors more easily and quickly, without having to wait on the phone or physically visit the doctor's office.
                    </p>
                </div>
                <img src="./Patientlogo.png" height="90" width="90" alt="Lifestyle" class="-z-50 md:mb-4 md:order-1">
            </div>
            <!-- Wedding service end -->

            <!-- Wedding service start -->
            <div class="flex flex-row md:flex-col justify-between items-center md:items-start my-8 md:w-1/3">
                <div class="w-1/3">
                    <img src="./PharmacyLogo.png" height="80" width="80" alt="Moments" class="-z-50 md:mb-4">
                </div>
                <div class="w-2/3 text-right md:text-left md:w-full">
                    <h1 class="uppercase text-2xl font-semibold">
                        Pharmacies
                    </h1>
                    <p class="capitalize text-stone-500">
                        Pharmacies can use the app to streamline their operations and improve the quality of service they provide to patients.
                    </p>
                </div>
            </div>
            <!-- Wedding service end -->
        </div>
        <!-- Services end -->

        <!-- Circle start -->
        <div class="bg-neutral-300 h-64 w-64 rounded-full absolute top-0 -right-20 mt-16 -z-20"></div>
        <!-- Circle end -->
	</section>
	<!-- Services section end -->
</template>

<script>
export default {

}
</script>

<style>

</style>