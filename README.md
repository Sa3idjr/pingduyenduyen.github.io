<title>Scout Members</title> <style> body { background-color: blue; /* Set background color to blue */ color: white; /* Set text color to white for better readability on blue background */ font-family: Arial, sans-serif; /* Set font family */ margin: 0; /* Remove default margin */ padding: 0; /* Remove default padding */ }
    header {
        background-color: #333; /* Dark background color for the header */
        padding: 20px;
        animation: slideInDown 1s ease;
    }

    header h1 {
        margin: 0;
    }

    .meeting {
        text-align: center;
        margin-bottom: 20px;
    }

    main {
        padding: 20px;
        margin-bottom: 60px; /* Increased margin to make space for the footer */
        animation: fadeIn 1s ease;
    }

    section {
        margin-bottom: 20px;
    }

    footer {
        background-color: #333; /* Dark background color for the footer */
        color: white;
        padding: 20px;
        position: fixed;
        bottom: 0;
        width: 100%;
        animation: slideInUp 1s ease;
    }

    label {
        display: block;
        margin-bottom: 10px;
    }

    input[type="text"], input[type="number"], textarea {
        width: 100%;
        padding: 10px;
        margin-bottom: 20px;
        border-radius: 5px;
        border: none;
        background-color: #444;
        color: white;
    }

    input[type="submit"] {
        background-color: #444;
        color: white;
        border: none;
        padding: 10px 20px;
        border-radius: 5px;
        cursor: pointer;
    }

    input[type="submit"]:hover {
        background-color: #666;
    }

    /* Add this CSS to make inputs readonly */
    input[readonly] {
        background-color: #666;
        cursor: not-allowed;
    }

    @keyframes fadeIn {
        from { opacity: 0; }
        to { opacity: 1; }
    }

    @keyframes slideInDown {
        from {
            transform: translateY(-100%);
            opacity: 0;
        }
        to {
            transform: translateY(0);
            opacity: 1;
        }
    }

    @keyframes slideInUp {
        from {
            transform: translateY(100%);
            opacity: 0;
        }
        to {
            transform: translateY(0);
            opacity: 1;
        }
    }
</style>
Welcome to Ping Duyen Duyen
Chieftain Merna

<main>
    <section class="meeting">
        <h2>Meeting:</h2>
        <h3>Date:</h3>
    </section>

    <section>
        <h2>Enter Member Details</h2>
        <form id="memberForm">
            <!-- Member 1 -->
            <label for="member1Name">Name of Member 1:</label>
            <input type="text" id="member1Name" name="member1Name" readonly value='Mavien Sherein'>

            <label for="member1Number">Number of Member 1:</label>
            <input type="text" id="member1Number" name="member1Number" readonly value='0120 600 5529'>
            <label for="member1Absent">Absent or Not(With excuse):</label>
            <input type="text" id="member1Absent" name="member1Absent" readonly value='Not'>

            <!-- Member 2 -->
            <label for="member2Name">Name of Member 2:</label>
            <input type="text" id="member2Name" name="member2Name" readonly value='Joy Hany'>

            <label for="member2Number">Number of Member 2:</label>
            <input type="text" id="member2Number" name="member2Number" readonly value='0122 057 4602'>
            <label for="member2Absent">Absent or Not(With excuse):</label>
            <input type="text" id="member2Absent" name="member2Absent" readonly value='Not'>

            <!-- Member 3 -->
            <label for="member3Name">Name of Member 3:</label>
            <input type="text" id="member3Name" name="member3Name" readonly value='George Mina'>

            <label for="member3Number">Number of Member 3:</label>
            <input type="text" id="member3Number" name="member3Number" readonly value='0127 976 6663'>
            <label for="member3Absent">Absent or Not(With excuse):</label>
            <input type="text" id="member3Absent" name="member3Absent" readonly value='Not'>

            <!-- Member 4 -->
            <label for="member4Name">Name of Member 4:</label>
            <input type="text" id="member4Name" name="member4Name" readonly value='Sarah Nasser'>

            <label for="member4Number">Number of Member 4:</label>
            <input type="text" id="member4Number" name="member4Number" readonly value='0127 810 4046'>
            <label for="member4Absent">Absent or Not(With excuse):</label>
            <input type="text" id="member4Absent" name="member4Absent" readonly value='Not'>

            <!-- Member 5 -->
            <label for="member5Name">Name of Member 5:</label>
            <input type="text" id="member5Name" name="member5Name" readonly value='Marly Hany'>

            <label for="member5Number">Number of Member 5:</label>
            <input type="text" id="member5Number" name="member5Number" readonly value='0127 011 1610'>
            <label for="member5Absent">Absent or Not(With excuse):</label>
            <input type="text" id="member5Absent" name="member5Absent" readonly value='Not'>

            <!-- Member 6 -->
            <label for="member6Name">Name of Member 6:</label>
            <input type="text" id="member6Name" name="member6Name" readonly value='Mirolla Raafat'>

            <label for="member6Number">Number of Member 6:</label>
            <input type="text" id="member6Number" name="member6Number" readonly value='0120 663 5850'>
            <label for="member6Absent">Absent or Not(With excuse):</label>
            <input type="text" id="member6Absent" name="member6Absent" readonly value='Not'>

            <!-- Member 7 -->
            <label for="member7Name">Name of Member 7:</label>
            <input type="text" id="member7Name" name="member7Name" readonly value='Fady Adel'>

            <label for="member7Number">Number of Member 7:</label>
            <input type="text" id="member7Number" name="member7Number" readonly value='0121 061 6237'>
            <label for="member7Absent">Absent or Not(With excuse):</label>
            <input type="text" id="member7Absent" name="member7Absent" readonly value='Not'>

            <!-- Member 8 -->
            <label for="member8Name">Name of Member 8:</label>
            <input type="text" id="member8Name" name="member8Name" readonly value='sa3id'>

            <label for="member8Number">Number of Member 8:</label>
            <input type="text" id="member8Number" name="member8Number" readonly value='0121 120 1408'>
            <label for="member8Absent">Absent or Not(With excuse):</label>
            <input type="text" id="member8Absent" name="member8Absent" readonly value='Not'>

            <!-- Member 9 -->
            <label for="member9Name">Name of Member 9:</label>
            <input type="text" id="member9Name" name="member9Name" readonly value='Mina Nader'>

            <label for="member9Number">Number of Member 9:</label>
            <input type="text" id="member9Number" name="member9Number" readonly value='0127 188 7057'>
            <label for="member9Absent">Absent or Not(With excuse):</label>
            <input type="text" id="member9Absent" name="member9Absent" readonly value='Not'>

            <!-- Member 10 -->
            <label for="member10Name">Name of Member 10:</label>
            <input type="text" id="member10Name" name="member10Name" readonly value='Marcelino Mamdouh'>

            <label for="member10Number">Number of Member 10:</label>
            <input type="text" id="member10Number" name="member10Number" readonly value='0127 289 5777'>
            <label for="member10Absent">Absent or Not(With excuse):</label>
            <input type="text" id="member10Absent" name="member10Absent" readonly value='Not'>

            <!-- Member 11 -->
            <label for="member11Name">Name of Member 11:</label>
            <input type="text" id="member11Name" name="member11Name" readonly value='Mariam Hany'>

            <label for="member11Number">Number of Member 11:</label>
            <input type="text" id="member11Number" name="member11Number" readonly value='0127 279 9097'>
            <label for="member11Absent">Absent or Not(With excuse):</label>
            <input type="text" id="member11Absent" name="member11Absent" readonly value='Not'>

            <!-- Member 12 -->
            <label for="member12Name">Name of Member 12:</label>
            <input type="text" id="member12Name" name="member12Name" readonly value='Eriny Nabil'>

            <label for="member12Number">Number of Member 12:</label>
            <input type="text" id="member12Number" name="member12Number" readonly value='0155 860 0442'>
            <label for="member12Absent">Absent or Not(With excuse):</label>
            <input type="text" id="member12Absent" name="member12Absent" readonly value='Not'>
        </form>
    </section>
</main>

<footer>
    <p>All Rights Reserved for Ping Duyen Duyen</p>
</footer>
